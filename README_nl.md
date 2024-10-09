<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# BookStack voor Yunohost

[![Integratieniveau](https://dash.yunohost.org/integration/bookstack.svg)](https://ci-apps.yunohost.org/ci/apps/bookstack/) ![Mate van functioneren](https://ci-apps.yunohost.org/ci/badges/bookstack.status.svg) ![Onderhoudsstatus](https://ci-apps.yunohost.org/ci/badges/bookstack.maintain.svg)

[![BookStack met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=bookstack)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je BookStack snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

BookStack is an opinionated wiki system that provides a pleasant and simple out of the box experience. New users to an instance should find the experience intuitive and only basic word-processing skills should be required to get involved in creating content on BookStack. The platform should provide advanced power features to those that desire it but they should not interfere with the core simple user experience.

### Features

- Multi-Factor Authentication
- Dark & Light Modes
- LDAP Authentication
- Markdown Editor
- WYSIWYG Editing
- Multi-Lingual
- Diagrams.net Integration


**Geleverde versie:** 24.10~ynh1

**Demo:** <https://demo.bookstackapp.com>

## Schermafdrukken

![Schermafdrukken van BookStack](./doc/screenshots/screenshot.png)

## Documentatie en bronnen

- Officiele website van de app: <https://www.bookstackapp.com>
- Officiele gebruikersdocumentatie: <https://www.bookstackapp.com/docs/user/>
- Officiele beheerdersdocumentatie: <https://www.bookstackapp.com/docs/admin/>
- Upstream app codedepot: <https://github.com/BookStackApp/BookStack>
- YunoHost-store: <https://apps.yunohost.org/app/bookstack>
- Meld een bug: <https://github.com/YunoHost-Apps/bookstack_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing --debug
of
sudo yunohost app upgrade bookstack -u https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
