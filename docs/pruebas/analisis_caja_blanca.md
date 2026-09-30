# Análisis de caja blanca

## Objetivo
El análisis de caja blanca permite verificar el comportamiento interno de componentes críticos. En este proyecto, se centra en la lógica de asignación de incidencias, validación de permisos y cálculo de métricas operativas.

## Módulos analizados
- `assignIncident`: valida prioridad, técnico disponible y estado actual.
- `validatePermissions`: comprueba roles y permisos del usuario autenticado.
- `buildReport`: agrega datos por fecha, equipo y prioridad.

## Técnicas aplicadas
- Revisión de ramas y condiciones.
- Verificación de bucles y casos límite.
- Validación de errores por entrada nula o tipos no esperados.

## Casos de prueba relevantes
1. Incidencia con prioridad alta asignada a técnico en turno correcto.
2. Incidencia duplicada con mismo origen y descripción.
3. Usuario sin permisos intenta cambiar el estado a resuelto.
4. Reporte generado con datos vacíos en algunos días del periodo.

## Cobertura esperada
Se pretende cubrir al menos:
- 90% de líneas en servicios de negocio.
- 85% de funciones de validación.
- 100% de rutas críticas con pruebas automatizadas.

## Observaciones
La prueba de caja blanca aporta mayor control sobre las decisiones de diseño y ayuda a prevenir errores de lógica que no aparecen en la capa de interfaz.