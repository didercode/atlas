# Caga2Dos Atlas · Archivo paranormal e investigación de campo

Aplicación web unificada con cuatro áreas:

- **Inicio:** buscador, estadísticas y accesos editoriales.
- **Expedientes:** 1.096 casos con filtros, favoritos, fuentes y relaciones.
- **Archivo de Campo:** checklist, riesgos, diario, registros, sesiones e informes privados.
- **Caga2Dos:** investigaciones, vídeos, shorts, directos, tecnología y archivo visual.

## Archivo de Campo

Los proyectos se guardan en el almacenamiento local del navegador. La aplicación permite:

- Consultar de un vistazo el checklist tecnológico, la evaluación de riesgos, el diario y el registro rápido.
- Crear una investigación desde cualquier expediente.
- Eliminar individualmente los cuadernos que ya no se necesiten, junto con sus registros locales.
- Preparar participantes, tecnología, objetivos y checklist.
- Iniciar, pausar, reabrir y cerrar una sesión.
- Registrar golpes, voces, Kinect, REM-Pod, Spirit Box, K2, observaciones y cambios ambientales.
- Guardar hora real y tiempo transcurrido de cada acontecimiento.
- Añadir zona, descripción, dispositivo y testigos.
- Clasificar registros durante la revisión.
- Generar un informe imprimible o PDF.
- Exportar e importar copias de seguridad JSON.

Los registros locales no se envían a ningún servidor desde esta versión.

## Publicación

Sube la carpeta completa a Netlify, Vercel, GitHub Pages o cualquier servidor estático. El archivo principal es `index.html`.

También puedes abrir `index.html` directamente para revisar la aplicación sin servidor. `data/data-bundle.js` contiene una copia generada de los datos para la vista local; los JSON separados se conservan como fuente editable y escalable.

## Archivos principales

```text
index.html
assets/css/app.css
assets/css/app-v3.css
assets/js/app-v3.js
data/expedientes.json
data/fuentes.json
data/investigaciones.json
data/estadisticas.json
data/data-bundle.js
service-worker.js
manifest.webmanifest
```

## Aviso editorial

Historia documentada no significa fenómeno paranormal demostrado. La aplicación separa observaciones, interpretaciones y estados de revisión, y recuerda respetar propiedades, permisos y seguridad.
