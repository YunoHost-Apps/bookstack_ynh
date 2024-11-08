<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# BookStack YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/bookstack.svg)](https://ci-apps.yunohost.org/ci/apps/bookstack/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/bookstack.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/bookstack.maintain.svg)

[![Instalatu BookStack YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=bookstack)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek BookStack YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

BookStack is an opinionated wiki system that provides a pleasant and simple out of the box experience. New users to an instance should find the experience intuitive and only basic word-processing skills should be required to get involved in creating content on BookStack. The platform should provide advanced power features to those that desire it but they should not interfere with the core simple user experience.

### Features

- Multi-Factor Authentication
- Dark & Light Modes
- LDAP Authentication
- Markdown Editor
- WYSIWYG Editing
- Multi-Lingual
- Diagrams.net Integration

**Paketatutako bertsioa:** 24.10.1~ynh1

**Demoa:** <https://demo.bookstackapp.com>

## Pantaila-argazkiak

![BookStack(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://www.bookstackapp.com>
- Erabiltzaileen dokumentazio ofiziala: <https://www.bookstackapp.com/docs/user/>
- Administratzaileen dokumentazio ofiziala: <https://www.bookstackapp.com/docs/admin/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/BookStackApp/BookStack>
- YunoHost Denda: <https://apps.yunohost.org/app/bookstack>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/bookstack_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing --debug
edo
sudo yunohost app upgrade bookstack -u https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
