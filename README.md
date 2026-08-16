# Alerta Sísmica JABM — versión con Investigación

Esta versión conserva el monitoreo de USGS, filtros de magnitud, selección de países, avisos del navegador, detalle de eventos, S.O.S. y sección Más, y añade una sección **Investigación**.

## Investigación integrada
- Resumen 2026 con los valores del estudio al 14 de agosto de 2026: 88 M6+, 11 M7+, objetivo central ≈125 M6+ y ≈15 M7+.
- Comparación actual vs escenario central 2026.
- Histórico M6+ desde 2000 usando la API FDSN de USGS.
- Distribución mensual de M6+ y M7+ observados en 2026.
- Próximo mes (septiembre 2026): ritmo teórico de ≈8 M6+ y ≈1 M7+ por mes para el escenario central del estudio; está marcado como ritmo teórico, no predicción.
- Proyección experimental 2027 con rangos y ventanas del material de investigación:
  - M7+: 12–18, Mar–Ago.
  - M6+: 50–70, Feb–Ago.
  - M5+: 150–250, Ene–Sep.
  - Enjambres: aumento Mar–Jul.
  - Ventanas de actividad relativa según las láminas de investigación.
- Advertencias metodológicas visibles para separar datos observados de proyecciones experimentales.

## Publicar en GitHub Pages
Sube `index.html`, `manifest.json`, `icon-192.png` e `icon-512.png` a la rama `main` y publica GitHub Pages desde esa rama.

## Importante
Una página estática de GitHub Pages no garantiza notificaciones push cuando la aplicación está cerrada. Esta versión conserva los avisos del navegador cuando el entorno puede ejecutarlos; para push fiable en segundo plano se requiere un servicio push/backend.

Las proyecciones de la sección Investigación son experimentales y no predicen terremotos individuales.
