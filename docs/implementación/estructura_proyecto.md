# Estructura del proyecto

## Organización de carpetas
```text
project-root/
├── src/
│   ├── app/
│   │   ├── routes/
│   │   ├── components/
│   │   └── pages/
│   ├── domain/
│   │   ├── entities/
│   │   ├── services/
│   │   └── validators/
│   ├── infrastructure/
│   │   ├── db/
│   │   ├── repositories/
│   │   └── clients/
│   └── shared/
│       ├── utils/
│       ├── constants/
│       └── types/
├── api/
│   ├── controllers/
│   ├── middleware/
│   └── routes/
├── tests/
│   ├── unit/
│   ├── integration/
│   └── e2e/
├── docs/
│   ├── analysis/
│   ├── design/
│   └── deployment/
├── Dockerfile
├── docker-compose.yml
├── package.json
├── README.md
└── .env.example
```

## Descripción de módulos
- `src/app`: contiene la capa de presentación y la lógica de navegación.
- `src/domain`: define entidades y reglas del negocio.
- `src/infrastructure`: encapsula acceso a datos y servicios externos.
- `api`: expone los endpoints HTTP para frontend y clientes externos.
- `tests`: cubre validación funcional y regresión.

## Convenciones
- Nomenclatura en inglés para archivos y variables de negocio.
- Estructura modular por dominio en lugar de por tipo de archivo.
- Validación de errores centralizada en middleware.

## Buenas prácticas aplicadas
- Componentización reutilizable.
- Separación de responsabilidades por capas.
- Documentación mínima en cada servicio importante.
- Control de versiones con ramas por funcionalidad y revisión de pull requests.