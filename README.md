# BookStack for YunoHost

[![Integration level](https://dash.yunohost.org/integration/bookstack.svg)](https://dash.yunohost.org/appci/app/bookstack) ![](https://ci-apps.yunohost.org/ci/badges/bookstack.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/bookstack.maintain.svg)  
[![Install BookStack with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=bookstack)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install BookStack quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview
BookStack is a simple, self-hosted, easy-to-use platform for organising and storing information. It is an opinionated wiki system that provides a pleasant and simple out of the box experience.

BookStack is built using PHP, on top of the Laravel framework and it uses MySQL to store data.

**Shipped version:** 21.04.4

## Screenshots

![](https://www.bookstackapp.com/images/bookstack-hero-screenshot.jpg)

## Demo

* [Official demo](https://demo.bookstackapp.com/)

## Configuration

For the first time Login, use the default credentials `admin@admin.com` and `password`. You should change these details immediately after logging in for the first time.

* How to configure this app: From an admin panel, a plain file with SSH, or any other way.

## Documentation

 * Official documentation: https://www.bookstackapp.com/docs/
 * YunoHost documentation: https://yunohost.org/en/app_bookstack

## YunoHost specific features

#### Multi-user support

 * Are LDAP and HTTP auth supported? **Yes**
 * Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/bookstack.svg)](https://ci-apps.yunohost.org/ci/apps/bookstack/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/bookstack.svg)](https://ci-apps-arm.yunohost.org/ci/apps/bookstack/)

## Limitations

* Any known limitations.

## Additional information

* Other info you would like to add about this app.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/bookstack_ynh/issues
 * App website: https://www.bookstackapp.com/
 * Upstream app repository: https://github.com/BookStackApp/BookStack
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing --debug
or
sudo yunohost app upgrade bookstack -u https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing --debug
```
