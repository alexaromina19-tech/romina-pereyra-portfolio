# Romina Pereyra — Portfolio

Portfolio de diseño de producto, gráfico y editorial: 17 proyectos, biografía y currículum.

La primera pantalla muestra el vídeo real de Romina trabajando en el taller: imagen nativa de 1280 × 720, en blanco y negro con las chispas en dorado, sin sonido y en un bucle suave de unos 4,5 segundos a 1,35× de velocidad. El nombre conserva la caligrafía Pinyon, ahora en amarillo intenso #ffe03b, con las especialidades en dorado suave #f4d57b; después aparecen las dos especialidades en Bodoni. El encuadre mantiene a la persona y la herramienta visibles en móvil y escritorio. El vídeo tiene control de pausa, se detiene fuera de pantalla y respeta movimiento reducido con una imagen fija. Solo cambia esta primera pantalla: la galería inferior conserva sus 17 proyectos, encuadres, orden y entradas al hacer scroll. Mescladís mantiene la vista azul con pasta y La Rambla el cartel negro sobre la columna con textura.

La fotografía MOCO de Time Out se recuperó completa del PDF original, sin recortes ni transparencia y con su fondo azul verdoso íntegro. Los títulos bajo las portadas vuelven a animarse también al navegar directamente de un proyecto a otro.

Las 17 portadas mantienen las letras, colores, proporciones y posición del PDF original. Los resultados incluyen 92 imágenes individuales; los procesos, 130. Las fotos finales y las de proceso forman galerías fijas: se muestran completas y con su proporción nativa, sin recortes dentro del marco. Los resultados conservan el orden y las filas de la composición original; el proceso añade un texto breve. Las imágenes tienen mayor separación y no llevan borde; el cuadro completo se eleva y crece al pasar el ratón. Al bajar por el inicio, por las 17 tarjetas de Proyectos y por las galerías de cada proyecto, las fotografías llegan una a una desde los lados y desde abajo, con giro, cambio de escala y un pequeño rebote al colocarse; las que entran juntas se escalonan cada 90 ms, sin esperas largas. La entrada se repite al volver arriba y bajar de nuevo. Los títulos de portada aparecen por partes con sus letras originales del PDF, primero el nombre principal y después la línea inferior. También se animan el título de la introducción, Proceso y el encabezado Proyectos. La galería final no lleva título visible; el proceso conserva su título y un texto breve. Cada imagen puede ampliarse al hacer clic. En móvil se usa una columna para mantener las fotografías grandes y completas. Las preferencias de movimiento reducido muestran todas las imágenes sin animación; el foco de teclado también las revela inmediatamente.

Sobre mí presenta primero el nombre y, al terminar su entrada, anima la biografía y las columnas del currículum. Al final incluye la foto completa de Romina con pantalla de protección y una herramienta en el taller, mostrada en blanco y negro sin modificar el archivo original. El currículum, la fotografía y la línea inferior tienen márgenes amplios.

## Publicación y rutas

GitHub Pages publica la rama `main`, directorio raíz. Las rutas usan fragmentos, como `#proyecto/kubik`, y funcionan al recargar sin reglas de servidor. Los archivos listos para publicar se generan en `dist/client/`.

## Código editable

Descarga el repositorio completo con **Code → Download ZIP** y descomprímelo. `portfolio-source.zip` contiene React/Vite, los datos, las fuentes y los iconos. Las fotografías WebP y el vídeo MP4 se encuentran junto a `index.html`, en la raíz del repositorio.

1. Descomprime `portfolio-source.zip` en una carpeta llamada `source`.
2. Copia los archivos `.webp` y `.mp4` de la raíz del repositorio a `source/public/`.
3. Dentro de `source`, ejecuta `npm install` y `npm run dev`.
4. Ejecuta `npm run build` para generar `dist/client/`.
5. Publica su contenido en la raíz del repositorio.

La carpeta local editable original se llama `portfolio`. `src/projects.json` define los proyectos; `src/detail-assets.json`, las galerías; `src/result-layouts.json`, la composición fija de las fotos finales; y `src/cover-layouts.json`, los títulos originales. `src/ParallaxHome.jsx` y `src/parallax-home.css` contienen el inicio.

## Tipografía e imágenes

Bodoni Moda, Pinyon Script, Anton, Space Mono y UnifrakturMaguntia: licencia SIL Open Font License en `font-licenses.txt`. Las portadas conservan The Seasons y Nautica como arte transparente del PDF, sin distribuir esas fuentes. Los iconos Lucide y su licencia figuran en `icon-licenses.txt`.

Las fotografías proceden del portfolio facilitado por Romina, se procesan con el tratamiento de color de PDFium y no llevan filtros de brillo ni color. Se conserva la resolución disponible en el PDF y se exportan sin compresión con pérdida, con perfil sRGB. No se amplían artificialmente las fotografías originales. Las tarjetas de Proyectos usan versiones horizontales de 16:10, reenmarcadas con ImageGen y fondos extendidos a partir de cada fotografía. Se guardan en archivos *-archive-focus.webp separados de los originales. Los encuadres específicos del inicio se aplican con ventanas CSS sobre los píxeles originales; IKEA muestra solo la silla, Vitra la silla completa, Grease ambas cajas más grandes y los wearables un encuadre cercano. Las fotografías y portadas dentro de cada ficha permanecen originales. Los proyectos de estudio y reinterpretación de marcas se presentan como trabajo de formación en diseño.

Referencias: https://lovable.dev/templates/websites/portfolio/parallax-artist-portfolio y https://michomichi.com/ . Contacto profesional: alexaromina30@gmail.com. Los enlaces de contacto abren un nuevo correo de Gmail con ese destinatario.
