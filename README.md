# Romina Pereyra — Portfolio

Portfolio de diseño de producto, gráfico y editorial: 17 proyectos, biografía y currículum.

El inicio sigue la plantilla Parallax Artist Portfolio de Lovable: fondo claro, doce imágenes propias en profundidad, desplazamiento con el ratón y el scroll, menú a pantalla completa y galería de los 17 proyectos. El nombre completo cambia entre cinco tipografías cada 580 ms. El resto de rutas conserva el fondo negro.

Las 17 portadas mantienen las letras, colores, proporciones y posición del PDF original. Los resultados incluyen 92 imágenes individuales; los procesos, 130. Las fotos finales se colocan de forma fija, con la misma composición y recortes del PDF, sin su marco blanco y con un ligero movimiento al pasar el ratón. El proceso mantiene el carrusel horizontal con flechas, arrastre, swipe y teclado, sin los párrafos del PDF. Cada imagen puede ampliarse. Las preferencias de movimiento reducido detienen las animaciones.

## Publicación y rutas

GitHub Pages publica la rama `main`, directorio raíz. Las rutas usan fragmentos, como `#proyecto/kubik`, y funcionan al recargar sin reglas de servidor. Los archivos listos para publicar se generan en `dist/client/`.

## Código editable

Descarga el repositorio completo con **Code → Download ZIP** y descomprímelo. `portfolio-source.zip` contiene React/Vite, los datos, las fuentes y los iconos. Las fotografías WebP se encuentran junto a `index.html`, en la raíz del repositorio.

1. Descomprime `portfolio-source.zip` en una carpeta llamada `source`.
2. Copia los archivos `.webp` de la raíz del repositorio a `source/public/`.
3. Dentro de `source`, ejecuta `npm install` y `npm run dev`.
4. Ejecuta `npm run build` para generar `dist/client/`.
5. Publica su contenido en la raíz del repositorio.

La carpeta local editable original se llama `portfolio`. `src/projects.json` define los proyectos; `src/detail-assets.json`, las galerías; `src/result-layouts.json`, la composición fija de las fotos finales; y `src/cover-layouts.json`, los títulos originales. `src/ParallaxHome.jsx` y `src/parallax-home.css` contienen el inicio.

## Tipografía e imágenes

Bodoni Moda, Pinyon Script, Anton, Space Mono y UnifrakturMaguntia: licencia SIL Open Font License en `font-licenses.txt`. Las portadas conservan The Seasons y Nautica como arte transparente del PDF, sin distribuir esas fuentes. Los iconos Lucide y su licencia figuran en `icon-licenses.txt`.

Las fotografías proceden del portfolio facilitado por Romina, se procesan con el tratamiento de color de PDFium y no llevan filtros de brillo ni color. Se conserva la resolución disponible en el PDF y se exportan sin compresión con pérdida, con perfil sRGB. No se amplían artificialmente las fotografías. Los proyectos de estudio y reinterpretación de marcas se presentan como trabajo de formación en diseño.

Referencias: https://lovable.dev/templates/websites/portfolio/parallax-artist-portfolio y https://michomichi.com/ . Contacto profesional: alexaromina30@gmail.com.
