<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Mostlymatter para Yunohost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/mostlymatter)](https://ci-apps.yunohost.org/ci/apps/mostlymatter/)
![Estado funcional](https://apps.yunohost.org/badge/state/mostlymatter)
![Estado En Mantención](https://apps.yunohost.org/badge/maintained/mostlymatter)

[![Instalar Mostlymatter con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mostlymatter)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarMostlymatter rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

Mostlymatter is a fork of Mattermost meant to remove the users and messages limits.
Mattermost is an open source platform for secure collaboration across the entire software development lifecycle. Mattermost is written in Go and React and runs as a single Linux binary with MySQL or PostgreSQL.

Mattermost Mobile and Desktop Apps are available [here](https://mattermost.com/download/)

### Features

- One-to-one and group messaging, file sharing, and unlimited search history
- Threaded messaging, emoji, and custom emoji
- Tools for custom branding
- Continuous archiving
- Multi-factor authentication
- Highly customizable third-party bots, integrations, and command line tools
- Extensive integration support via webhooks, APIs, drivers, and third-party extensions
- Easily scalable to dozens of users per team
- Runtime profiling data and system monitoring reports


**Versión actual:** 10.4.2~ynh1

## Capturas

![Captura de Mostlymatter](./doc/screenshots/screenshot.png)

## Documentaciones y recursos

- Repositorio del código fuente oficial de la aplicación : <https://framagit.org/framasoft/framateam/mostlymatter>
- Catálogo YunoHost: <https://apps.yunohost.org/app/mostlymatter>
- Reportar un error: <https://github.com/YunoHost-Apps/mostlymatter_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/mostlymatter_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/mostlymatter_ynh/tree/testing --debug
o
sudo yunohost app upgrade mostlymatter -u https://github.com/YunoHost-Apps/mostlymatter_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
