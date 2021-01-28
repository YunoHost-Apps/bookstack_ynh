# BookStack for YunoHost

[![Integration level](https://dash.yunohost.org/integration/bookstack.svg)](https://dash.yunohost.org/appci/app/bookstack) ![](https://ci-apps.yunohost.org/ci/badges/bookstack.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/bookstack.maintain.svg)  
[![Install BookStack with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=bookstack)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install BookStack quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Quick description of this app.

**Shipped version:** 0.31.4

## Screenshots

![](https://www.bookstackapp.com/images/screenshots/page-view.png)

## Demo

* [Official demo](https://www.bookstackapp.com/#demo)

## Configuration

How to configure this app: From an admin panel, a plain file with SSH, or any other way.

## Documentation

 * Official documentation: https://www.bookstackapp.com/docs/
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

Are LDAP and HTTP auth supported?
Can the app be used by multiple users?

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/bookstack%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/bookstack/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/bookstack%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/bookstack/)

## Limitations

* Any known limitations.

## Additional information

* Other info you would like to add about this app.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/bookstack_ynh/issues
 * App website: Link to the official website of this app.
 * Upstream app repository: https://github.com/BookStackApp/BookStack
 * YunoHost website: https://yunohost.org/

---

## Developer info

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing --debug
or
sudo yunohost app upgrade bookstack -u https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing --debug
```
