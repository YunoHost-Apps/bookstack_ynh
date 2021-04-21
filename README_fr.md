# BookStack pour YunoHost

[![Integration level](https://dash.yunohost.org/integration/bookstack.svg)](https://dash.yunohost.org/appci/app/bookstack) ![](https://ci-apps.yunohost.org/ci/badges/bookstack.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/bookstack.maintain.svg)  
[![Installer BookStack avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=bookstack)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer BookStack rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Overview
BookStack est une plate-forme simple, auto-hébergée et facile à utiliser pour organiser et stocker des informations.

**Version incluse :** 21.04.2

## Screenshots

![](https://www.bookstackapp.com/images/bookstack-hero-screenshot.jpg)

## Démo

* [Démo officielle](https://demo.bookstackapp.com/)

## Configuration

Login using the default admin details `admin@admin.com` with a password of `password`. You should change these details immediately after logging in for the first time.

 * How to configure this app: From an admin panel, a plain file with SSH, or any other way.

## Documentation

 * Documentation officielle : https://www.bookstackapp.com/docs/
 * Documentation YunoHost : https://yunohost.org/fr/app_bookstack

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP et HTTP est-elle prise en charge ? **Oui**
* L'application peut-elle être utilisée par plusieurs utilisateurs ? **Oui**

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/bookstack.svg)](https://ci-apps.yunohost.org/ci/apps/bookstack/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/bookstack.svg)](https://ci-apps-arm.yunohost.org/ci/apps/bookstack/)

## Limitations

* Limitations connues.

## Informations additionnelles

* Autres informations que vous souhaitez ajouter sur cette application.

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/bookstack_ynh/issues
 * Site de l'application : https://www.bookstackapp.com/
 * Dépôt de l'application principale : https://github.com/BookStackApp/BookStack
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing --debug
or
sudo yunohost app upgrade bookstack -u https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing --debug
```
