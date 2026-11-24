# DRIVE CONTROL — Prototipo navegable 0.1

## Cómo probarlo
1. Descarga y descomprime `drive-control-prototipo.zip`.
2. Abre `index.html` en Chrome, Edge, Safari o Firefox.
3. Navega desde el menú lateral (computadora) o menú inferior (celular).
4. Registra jornadas, combustible, gastos y mantenimientos.
5. Consulta Análisis e Historial. Puedes exportar el historial a CSV.

## Alcance de esta versión
- Prototipo front-end navegable.
- Formularios funcionales y cálculos básicos.
- Los datos se guardan en `localStorage` del navegador/dispositivo.
- No requiere APK ni servidor para probarlo.

## Importante
Esta versión NO es todavía la aplicación de producción:
- No sincroniza datos entre dispositivos.
- No tiene inicio de sesión ni base de datos en la nube.
- No incluye todavía depreciación automática, importación Uber, archivos adjuntos, copias de seguridad ni cálculos contables completos.
- Los valores iniciales del dashboard son ilustrativos cuando aún no hay registros.

## Siguiente fase
Conectar la interfaz a Supabase (Auth + PostgreSQL + Storage), añadir seguridad por usuario y terminar el motor de rentabilidad con depreciación, costos fijos y reservas.
