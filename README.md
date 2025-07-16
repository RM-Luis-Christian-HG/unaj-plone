# UNAJ Plone Portal

Repositorio con la configuración base de Plone 6 + Volto para el portal de gestión de proyectos de investigación formativa de la Universidad Nacional de Juliaca.

## Estructura del proyecto

- `docker-compose.yml`: definición de servicios frontend, backend, nginx
- `default.conf`: configuración NGINX
- `unaj-plone_data_backup.tar.gz`: (debe subirse manualmente si se necesita restaurar datos)

## Cómo usar

1. Clonar este repo en otro equipo
2. Modificar el composer.yml, en frontend en la linea RAZZLE_API_PATH: http://@IP_PUBLICA/++api++, con tu IP de EC2 propia.
3. Restaurar el volumen de datos
4. Ejecutar `docker-compose up -d`
