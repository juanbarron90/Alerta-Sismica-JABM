# Alerta Sísmica JABM — versión con selección de países

Archivos para subir al repositorio GitHub Pages:
- `index.html` — aplicación actualizada.
- `manifest.json` — configuración PWA.
- `icon-512.png` — icono de la app.

Cambios principales:
- Magnitud mínima desde M3+ hasta M8+.
- Selección de uno o varios países.
- Botón “Todos” y “Limpiar”.
- Buscador de países.
- La selección se guarda en el iPhone con localStorage.
- Los eventos y avisos dentro de la página respetan la magnitud y los países seleccionados.
- Los detalles del evento muestran magnitud, ubicación, latitud, longitud, profundidad, tipo de magnitud, tsunami/alerta cuando USGS los reporta y enlace al evento.

Nota: esta versión todavía genera avisos del navegador mientras la página está abierta. Las notificaciones Push con la app cerrada requieren configurar el servicio Push/backend en un siguiente paso.
