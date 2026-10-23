# Romina Pereyra — Portfolio

Portfolio de diseño de producto, gráfico y editorial. Incluye 17 proyectos con descripción, imágenes de resultado y proceso, además de biografía y currículum.

El diseño adapta la composición de michomichi.com al fondo negro y al nombre completo de Romina, que alterna automáticamente entre cinco tipografías. Los textos y fotografías proceden del portfolio facilitado por Romina; los proyectos de estudio y reinterpretación de marcas se presentan como trabajo de formación en diseño.

## Sitio publicado

GitHub Pages publica los archivos de esta carpeta desde la rama `main`, directorio raíz. Las rutas internas usan fragmentos (`#proyecto/kubik`), por lo que los enlaces directos y la recarga funcionan sin reglas de servidor.

## Código fuente

`portfolio-source.zip` contiene el proyecto React/Vite editable, los datos en `src/projects.json` y las imágenes en `public/`.

1. Descomprime el archivo en una carpeta.
2. Ejecuta `npm install` y `npm run dev` para abrir la versión de desarrollo.
3. Ejecuta `npm run build`. Los archivos estáticos para publicar quedan en `dist/client/`.
4. Actualiza los archivos de la web con el contenido de `dist/client/`.

La carpeta local editable original se llama `portfolio`.

## Tipografía e imágenes

Bodoni Moda, Pinyon Script, Anton, Space Mono y UnifrakturMaguntia se distribuyen bajo la licencia SIL Open Font License, incluida en `font-licenses.txt`. Sustituyen las fuentes The Seasons y Nautica del PDF original. Las imágenes están optimizadas en WebP y se sirven desde el propio repositorio.

Contacto profesional: alexaromina30@gmail.com.


El inicio muestra los 17 proyectos en filas. Cada tarjeta reproduce al pasar el ratón o recibir foco una secuencia de tres fotografías reales con transiciones y movimiento. Estas imágenes se cargan al activar la tarjeta. Las preferencias de movimiento reducido detienen las animaciones.

