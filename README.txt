UDANETFLIX — instrucciones de actualización

Este paquete contiene una nueva versión de index.html y una copia de referencia de movies.json.
Para actualizar una web ya publicada, sustituye SOLO el index.html de tu proyecto por este archivo.
Conserva tu movies.json real, tus carpetas videos/ y caratulas/ y los nombres de archivo que ya utilizas.

PÓSTERES
- Si guardas una imagen en caratulas/pelicula-01.jpeg, puedes poner en movies.json:
  "poster": "caratulas/pelicula-01.jpeg"
- También admite el nombre sin carpeta, por ejemplo:
  "poster": "pelicula-01.jpeg"
  En ese caso prueba primero caratulas/pelicula-01.jpeg y después pelicula-01.jpeg.
- Los nombres y extensiones deben coincidir exactamente (incluyendo .jpg frente a .jpeg).
- Si un póster no carga, la tarjeta vuelve a mostrar el degradado definido en "colors".

PANTALLA DE PELÍCULA
Al hacer clic en una tarjeta se abre la pantalla de detalles con "Reproducir" y "Ver desde el principio".
El progreso se conserva solo durante la sesión actual de la página, no después de cerrarla o recargarla.

PUBLICACIÓN
Sube el index.html nuevo junto con tu movies.json actual y las carpetas videos/ y caratulas/ a Cloudflare Pages.
No subas el movies.json de referencia por encima de tu archivo real, porque contiene títulos de ejemplo.
