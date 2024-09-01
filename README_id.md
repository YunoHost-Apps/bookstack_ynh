<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# BookStack untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/bookstack.svg)](https://ci-apps.yunohost.org/ci/apps/bookstack/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/bookstack.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/bookstack.maintain.svg)

[![Pasang BookStack dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=bookstack)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang BookStack secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

BookStack is an opinionated wiki system that provides a pleasant and simple out of the box experience. New users to an instance should find the experience intuitive and only basic word-processing skills should be required to get involved in creating content on BookStack. The platform should provide advanced power features to those that desire it but they should not interfere with the core simple user experience.

### Features

- Multi-Factor Authentication
- Dark & Light Modes
- LDAP Authentication
- Markdown Editor
- WYSIWYG Editing
- Multi-Lingual
- Diagrams.net Integration


**Versi terkirim:** 24.05.4~ynh2

**Demo:** <https://demo.bookstackapp.com>

## Tangkapan Layar

![Tangkapan Layar pada BookStack](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://www.bookstackapp.com>
- Dokumentasi pengguna resmi: <https://www.bookstackapp.com/docs/user/>
- Dokumentasi admin resmi: <https://www.bookstackapp.com/docs/admin/>
- Depot kode aplikasi hulu: <https://github.com/BookStackApp/BookStack>
- Gudang YunoHost: <https://apps.yunohost.org/app/bookstack>
- Laporkan bug: <https://github.com/YunoHost-Apps/bookstack_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing --debug
atau
sudo yunohost app upgrade bookstack -u https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
