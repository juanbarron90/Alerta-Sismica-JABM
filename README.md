# Alerta Sísmica JABM

Versión actualizada para GitHub Pages.

## Incluye
- Diseño oscuro moderno tipo app móvil.
- Datos sísmicos en tiempo real desde USGS.
- Tarjetas M4.5+, M6+ y M7+ de las últimas 24 horas.
- Filtro de magnitud desde M3 hasta M8+.
- Selección de uno, varios o todos los países para eventos y avisos.
- Detalle de cada sismo con magnitud, ubicación, profundidad, latitud, longitud, tipo de magnitud, ID, estado, tsunami, alerta y significancia.
- **S.O.S. como ventana emergente:** permite elegir país y muestra botones **Llamar** para policía, bomberos y emergencias.
- **Más como ventana emergente:** información del creador, fuentes de datos, avisos y funcionamiento.
- Preferencias guardadas en el dispositivo.
- Solicitud y control de notificaciones del navegador.

## S.O.S.
Incluye México, Nicaragua, Costa Rica, Estados Unidos, Guatemala, El Salvador, Honduras, Colombia, Chile, Japón, Indonesia, Perú y Ecuador.

**Importante:** los números de emergencia deben verificarse con fuentes oficiales antes de depender de ellos durante una emergencia.

## GitHub Pages
Sube `index.html`, `manifest.json`, `icon-192.png` y `icon-512.png` a la rama `main` y publica GitHub Pages desde esa rama.

## Notificaciones
Una página estática de GitHub Pages no puede garantizar notificaciones push cuando la web está completamente cerrada. Para alertas fiables en segundo plano se necesita un servicio Web Push/backend o una función serverless.
