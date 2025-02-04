<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Mostlymatter untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/mostlymatter)](https://ci-apps.yunohost.org/ci/apps/mostlymatter/)
![Status kerja](https://apps.yunohost.org/badge/state/mostlymatter)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/mostlymatter)

[![Pasang Mostlymatter dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mostlymatter)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Mostlymatter secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

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


**Versi terkirim:** 10.4.2~ynh1

## Tangkapan Layar

![Tangkapan Layar pada Mostlymatter](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Depot kode aplikasi hulu: <https://framagit.org/framasoft/framateam/mostlymatter>
- Gudang YunoHost: <https://apps.yunohost.org/app/mostlymatter>
- Laporkan bug: <https://github.com/YunoHost-Apps/mostlymatter_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/mostlymatter_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/mostlymatter_ynh/tree/testing --debug
atau
sudo yunohost app upgrade mostlymatter -u https://github.com/YunoHost-Apps/mostlymatter_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
