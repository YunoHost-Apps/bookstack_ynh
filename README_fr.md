# BookStack pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/bookstack.svg)](https://dash.yunohost.org/appci/app/bookstack) ![](https://ci-apps.yunohost.org/ci/badges/bookstack.status.svg)  ![](https://ci-apps.yunohost.org/ci/badges/bookstack.maintain.svg)
[![Installer bookstack avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=bookstack)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install bookstack quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Vue d'ensemble

Plateforme pour créer du contenu de documentation/wiki 

**Version incluse:** 21.04.6~ynh1

**Démo:** https://demo.bookstackapp.com


## Captures d'écran


   ![](./doc/screenshots/bookstack-hero-screenshot.jpg)




## Avertissements / informations importantes

## Configuration

Login using the default admin details `admin@admin.com` with a password of `password`. You should change these details immediately after logging in for the first time.



## Documentations et ressources

* Site official de l'app : https://www.bookstackapp.com
* Documentation officielle utilisateur: https://yunohost.org/en/app_bookstack
* Documentation officielle de l'admin: https://www.bookstackapp.com/docs
* Dépôt de code officiel de l'app:  https://github.com/BookStackApp/BookStack
* Documentation YunoHost pour cette app: https://yunohost.org/app_bookstack
* Signaler un bug: https://github.com/YunoHost-Apps/bookstack_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing --debug
or
sudo yunohost app upgrade bookstack -u https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications:** https://yunohost.org/packaging_apps