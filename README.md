angularjs-gulp-browserify-boilerplate
=====================================

Fork del repositorio https://github.com/jakemmarsh/angularjs-gulp-browserify-boilerplate para probar GitHub Pages habilitado en el directorio /docs de la rama master.

### Instalación y arranque

1. Clonar el repositorio.
2. Ejecutar `npm install` desde la raíz del proyecto.
3. Ejecutar `npm run dev` para probar en local.
4. Para generar el código para producción ejecutar el script `npm run build`.

Notas:

- Se modificó el fichero `gulp/config.js` para que la salida se genere en el directorio /docs, directorio desde donde GitHub Pages publicará el contenido web.

- Se modificó index.html cambiando la etiqueta base para que no apunte a root sino al directorio del proyecto.

Las distintas posibilidades de publicación con GitHub Pages las explico en https://github.com/cristinafsanz/github-pages.