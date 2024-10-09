<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# BookStack pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/bookstack.svg)](https://ci-apps.yunohost.org/ci/apps/bookstack/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/bookstack.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/bookstack.maintain.svg)

[![Installer BookStack avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=bookstack)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer BookStack rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

BookStack est un système wiki simple prête à l'emploi. Les nouveaux utilisateurs d'une instance devraient trouver l'expérience intuitive et seules des compétences de base en traitement de texte devraient être requises pour s'impliquer dans la création de contenu sur BookStack. La plate-forme doit fournir des fonctionnalités avancées à ceux qui le souhaitent, mais elles ne doivent pas interférer avec l'expérience utilisateur simple de base.

### Caractéristiques

- Authentification multifacteur
- Modes sombre et clair
- Authentification LDAP
- Éditeur Markdown facultatif
- Multilingue


**Version incluse :** 24.10~ynh1

**Démo :** <https://demo.bookstackapp.com>

## Captures d’écran

![Capture d’écran de BookStack](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://www.bookstackapp.com>
- Documentation officielle utilisateur : <https://www.bookstackapp.com/docs/user/>
- Documentation officielle de l’admin : <https://www.bookstackapp.com/docs/admin/>
- Dépôt de code officiel de l’app : <https://github.com/BookStackApp/BookStack>
- YunoHost Store : <https://apps.yunohost.org/app/bookstack>
- Signaler un bug : <https://github.com/YunoHost-Apps/bookstack_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing --debug
ou
sudo yunohost app upgrade bookstack -u https://github.com/YunoHost-Apps/bookstack_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
