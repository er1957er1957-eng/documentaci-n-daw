# Despliegue con GitHub Pages

## Propósito
La documentación técnica del proyecto se publica en GitHub Pages para facilitar la consulta por parte del equipo, clientes y revisores del proyecto.

## Requisitos previos
- Repositorio GitHub público o con acceso configurado.
- Proyecto Docusaurus ya inicializado.
- Permisos para desplegar páginas desde la rama `gh-pages` o mediante GitHub Actions.

## Configuración recomendada
1. Compilar la documentación con `npm run build`.
2. Preparar el directorio `build` para publicación.
3. Activar GitHub Pages en la configuración del repositorio.
4. Seleccionar la fuente de despliegue apropiada.

## Comandos de ejemplo
```bash
npm install
npm run build
```

## Flujo de despliegue
- Se genera la versión de producción del sitio.
- Los artefactos estáticos se publican en GitHub Pages.
- El sitio queda accesible mediante una URL pública del repositorio.

## Recomendaciones
- Mantener la documentación alineada con el código del proyecto.
- Usar versiones del documento para cambios relevantes.
- Automatizar el despliegue con GitHub Actions para evitar errores manuales.

## Beneficios
- Acceso sencillo desde cualquier navegador.
- Actualización rápida tras cada despliegue.
- Revisión centralizada de la arquitectura, requisitos y guía de implementación.