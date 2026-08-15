# Alerta Sísmica JABM

Versión renovada de la aplicación web para GitHub Pages.

## Incluye
- Diseño oscuro moderno estilo app móvil.
- Datos en tiempo real desde USGS.
- Tarjetas M4.5+, M6+ y M7+ de las últimas 24 horas.
- Filtro de magnitud desde M3 hasta M8+.
- Selección de uno, varios o todos los países para filtrar eventos y avisos.
- Búsqueda de países.
- Al tocar cualquier sismo se abre su detalle: magnitud, ubicación, profundidad, latitud, longitud, tipo de magnitud, ID, estado, tsunami, alerta, significancia y actualización.
- Botones para abrir el evento en USGS y las coordenadas en el mapa.
- Preferencias guardadas en el dispositivo.
- Solicitud y control de notificaciones del navegador.

## GitHub Pages
Sube los archivos del ZIP a la rama `main` y configura GitHub Pages para publicar desde esa rama.

## Importante sobre notificaciones
Una página estática de GitHub Pages no puede garantizar notificaciones push cuando la web está completamente cerrada. Esta versión activa notificaciones del navegador cuando el entorno permite ejecutarlas, pero para alertas fiables en segundo plano hace falta añadir un servicio push/backend (por ejemplo, Web Push con un servidor o una función serverless).
