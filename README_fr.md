<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Mostlymatter pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/mostlymatter)](https://ci-apps.yunohost.org/ci/apps/mostlymatter/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/mostlymatter)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/mostlymatter)

[![Installer Mostlymatter avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mostlymatter)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Mostlymatter rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Mostlymatter est un fork de Mattermost destiné à supprimer les limites d'utilisateurs et de messages.
Mattermost est une plateforme open source pour une collaboration sécurisée tout au long du cycle de vie du développement logiciel. Mattermost est écrit en Go et React et fonctionne comme un binaire Linux unique avec MySQL ou PostgreSQL.

### Fonctionnalités

- Messagerie individuelle et de groupe, partage de fichiers et historique de recherche illimité
- Messagerie, emoji et emoji personnalisés
- Outils pour une image de marque personnalisée
- Archivage continu
- Authentification multi-facteurs
- Bots tiers hautement personnalisables, intégrations et outils de ligne de commande
- Prise en charge étendue de l'intégration via des webhooks, des API, des pilotes et des extensions tierces
- Facilement évolutif à des dizaines d'utilisateurs par équipe
- Données de profilage d'exécution et rapports de surveillance du système


**Version incluse :** 10.4.2~ynh1

## Captures d’écran

![Capture d’écran de Mostlymatter](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Dépôt de code officiel de l’app : <https://framagit.org/framasoft/framateam/mostlymatter>
- YunoHost Store : <https://apps.yunohost.org/app/mostlymatter>
- Signaler un bug : <https://github.com/YunoHost-Apps/mostlymatter_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/mostlymatter_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/mostlymatter_ynh/tree/testing --debug
ou
sudo yunohost app upgrade mostlymatter -u https://github.com/YunoHost-Apps/mostlymatter_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
