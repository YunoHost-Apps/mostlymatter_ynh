<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Mostlymatter dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/mostlymatter)](https://ci-apps.yunohost.org/ci/apps/mostlymatter/)
![Status działania](https://apps.yunohost.org/badge/state/mostlymatter)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/mostlymatter)

[![Zainstaluj Mostlymatter z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mostlymatter)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Mostlymatter na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

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


**Dostarczona wersja:** 10.4.2~ynh1

## Zrzuty ekranu

![Zrzut ekranu z Mostlymatter](./doc/screenshots/screenshot.png)

## Dokumentacja i zasoby

- Repozytorium z kodem źródłowym: <https://framagit.org/framasoft/framateam/mostlymatter>
- Sklep YunoHost: <https://apps.yunohost.org/app/mostlymatter>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/mostlymatter_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/mostlymatter_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/mostlymatter_ynh/tree/testing --debug
lub
sudo yunohost app upgrade mostlymatter -u https://github.com/YunoHost-Apps/mostlymatter_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
