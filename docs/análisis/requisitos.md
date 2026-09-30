# Análisis de requisitos

## 1. Requisitos funcionales
- RF-01: El sistema debe permitir el registro e inicio de sesión de usuarios con roles definidos.
- RF-02: Los usuarios con perfil técnico podrán consultar, asignar y cambiar el estado de las incidencias.
- RF-03: Los administradores podrán crear categorías, prioridades y reglas de workflow para cada tipo de incidencia.
- RF-04: El sistema deberá generar informes de rendimiento por técnico, servicio y periodo temporal.
- RF-05: Cada resolución deberá dejar constancia del tiempo empleado, intervención realizada y documentación asociada.

## 2. Requisitos no funcionales
- RNF-01: La API debe responder en menos de 200 ms para consultas simples bajo carga normal.
- RNF-02: La disponibilidad objetivo es del 99.9% durante el periodo de producción.
- RNF-03: La aplicación debe soportar 500 usuarios concurrentes sin degradación crítica del servicio.
- RNF-04: Los datos sensibles deben almacenarse cifrados y estar protegidos mediante autenticación y control de acceso por roles.

## 3. Casos de uso principales
- Registrar una incidencia desde un formulario web.
- Asignar una incidencia a un técnico concreto.
- Actualizar el estado y adjuntar evidencia.
- Generar un informe semestral de incidencias.
