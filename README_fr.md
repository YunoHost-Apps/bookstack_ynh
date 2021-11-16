# BookStack pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/bookstack.svg)](https://dash.yunohost.org/appci/app/bookstack) ![](https://ci-apps.yunohost.org/ci/badges/bookstack.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/bookstack.maintain.svg)  
[![Installer BookStack avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=bookstack)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer BookStack rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

BookStack is an opinionated wiki system that provides a pleasant and simple out of the box experience. New users to an instance should find the experience intuitive and only basic word-processing skills should be required to get involved in creating content on BookStack. The platform should provide advanced power features to those that desire it but they should not interfere with the core simple user experience.


**Version incluse :** 21.11~ynh1

**Démo :** https://demo.bookstackapp.com

## Captures d'écran

![](./doc/screenshots/bookstack-hero-screenshot.jpg)

## Avertissements / informations importantes

## Configuration

Login using the default admin details `admin@admin.com` with a password of `password`. You should change these details immediately after logging in for the first time.

## Documentations et ressources

* Site officiel de l'app : https://www.bookstackapp.com
* Documentation officielle de l'admin : https://www.bookstackapp.com/docs
* Dépôt de code officiel de l'app : https://github.com/BookStackApp/BookStack
* Documentation YunoHost pour cette app : https://yunohost.org/app_bookstack
* Signaler un bug : https://github.com/YunoHost-Apps/bookstack_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing --debug
ou
sudo yunohost app upgrade bookstack -u https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps