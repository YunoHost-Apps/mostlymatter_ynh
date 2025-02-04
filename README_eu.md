<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Mostlymatter YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/mostlymatter)](https://ci-apps.yunohost.org/ci/apps/mostlymatter/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/mostlymatter)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/mostlymatter)

[![Instalatu Mostlymatter YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mostlymatter)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Mostlymatter YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

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


**Paketatutako bertsioa:** 10.4.2~ynh1

## Pantaila-argazkiak

![Mostlymatter(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Jatorrizko aplikazioaren kode-gordailua: <https://framagit.org/framasoft/framateam/mostlymatter>
- YunoHost Denda: <https://apps.yunohost.org/app/mostlymatter>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/mostlymatter_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/mostlymatter_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/mostlymatter_ynh/tree/testing --debug
edo
sudo yunohost app upgrade mostlymatter -u https://github.com/YunoHost-Apps/mostlymatter_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
