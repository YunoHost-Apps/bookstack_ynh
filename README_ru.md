<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# BookStack для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/bookstack)](https://ci-apps.yunohost.org/ci/apps/bookstack/)
![Состояние работы](https://apps.yunohost.org/badge/state/bookstack)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/bookstack)

[![Установите BookStack с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=bookstack)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить BookStack быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

BookStack is an opinionated wiki system that provides a pleasant and simple out of the box experience. New users to an instance should find the experience intuitive and only basic word-processing skills should be required to get involved in creating content on BookStack. The platform should provide advanced power features to those that desire it but they should not interfere with the core simple user experience.

### Features

- Multi-Factor Authentication
- Dark & Light Modes
- LDAP Authentication
- Markdown Editor
- WYSIWYG Editing
- Multi-Lingual
- Diagrams.net Integration


**Поставляемая версия:** 24.10.3~ynh1

**Демо-версия:** <https://demo.bookstackapp.com>

## Снимки экрана

![Снимок экрана BookStack](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://www.bookstackapp.com>
- Официальная документация пользователя: <https://www.bookstackapp.com/docs/user/>
- Официальная документация администратора: <https://www.bookstackapp.com/docs/admin/>
- Репозиторий кода главной ветки приложения: <https://github.com/BookStackApp/BookStack>
- Магазин YunoHost: <https://apps.yunohost.org/app/bookstack>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/bookstack_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing --debug
или
sudo yunohost app upgrade bookstack -u https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
