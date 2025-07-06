# UNAJ Plone Portal

Repositorio con la configuración base de Plone 6 + Volto para el portal de gestión de proyectos de investigación formativa de la Universidad Nacional de Juliaca.

## Estructura del proyecto

- `docker-compose.yml`: definición de servicios frontend, backend, nginx
- `default.conf`: configuración NGINX
- `unaj-plone-data.tar.gz`: (debe subirse manualmente si se necesita restaurar datos)

## Cómo usar

1. Clonar este repo en otro equipo
2. Restaurar el volumen de datos
3. Ejecutar `docker-compose up -d`
