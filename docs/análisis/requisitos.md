# Análisis de Requisitos

## 1. Requisitos Funcionales (RF)
* **RF-01 (Autenticación):** El sistema debe permitir el inicio de sesión mediante credenciales únicas (correo y contraseña) o tokens OAuth2.
* **RF-02 (Gestión de Recursos):** Los usuarios administradores podrán crear, modificar y dar de baja lógica los elementos del inventario.
* **RF-03 (Generación de Reportes):** El sistema exportará informes operativos en formatos PDF y CSV.

## 2. Requisitos No Funcionales (RNF)
* **RNF-01 (Rendimiento):** Las peticiones a la API principal no deben superar un tiempo de respuesta de 200 ms.
* **RNF-02 (Disponibilidad):** La plataforma mantendrá un SLA del 99.9% en producción.
