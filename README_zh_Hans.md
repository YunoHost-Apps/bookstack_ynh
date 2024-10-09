<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 BookStack

[![集成程度](https://dash.yunohost.org/integration/bookstack.svg)](https://ci-apps.yunohost.org/ci/apps/bookstack/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/bookstack.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/bookstack.maintain.svg)

[![使用 YunoHost 安装 BookStack](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=bookstack)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 BookStack。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

BookStack is an opinionated wiki system that provides a pleasant and simple out of the box experience. New users to an instance should find the experience intuitive and only basic word-processing skills should be required to get involved in creating content on BookStack. The platform should provide advanced power features to those that desire it but they should not interfere with the core simple user experience.

### Features

- Multi-Factor Authentication
- Dark & Light Modes
- LDAP Authentication
- Markdown Editor
- WYSIWYG Editing
- Multi-Lingual
- Diagrams.net Integration


**分发版本：** 24.10~ynh1

**演示：** <https://demo.bookstackapp.com>

## 截图

![BookStack 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://www.bookstackapp.com>
- 官方用户文档： <https://www.bookstackapp.com/docs/user/>
- 官方管理文档： <https://www.bookstackapp.com/docs/admin/>
- 上游应用代码库： <https://github.com/BookStackApp/BookStack>
- YunoHost 商店： <https://apps.yunohost.org/app/bookstack>
- 报告 bug： <https://github.com/YunoHost-Apps/bookstack_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing --debug
或
sudo yunohost app upgrade bookstack -u https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
