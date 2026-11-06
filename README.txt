CORE - Invitación Fiesta de fin de año 2026

Archivos para Render Static Site:
  index.html: invitación interactiva
  preview-core.png: portada 1200 x 630 sin raya naranja
  favicon.ico y favicon.png: ícono de marca

Subir LOS ARCHIVOS (no el ZIP) a la raíz de un repositorio nuevo de GitHub.
Render > New > Static Site > seleccionar repositorio.
Branch: main
Build Command: echo "Static site ready"
Publish Directory: .

IMPORTANTE: luego del primer deploy, cambiar los valores de og:image y
twitter:image en index.html por la URL COMPLETA asignada por Render:
https://NOMBRE.onrender.com/preview-core.png
Además agregar la etiqueta og:url con https://NOMBRE.onrender.com/
Guardar/commit y esperar el segundo deploy. Esto hace la vista previa
más confiable en WhatsApp.

El botón de calendario abre Google Calendar con evento de día completo
(10/12/2026) porque no se especificó horario.
