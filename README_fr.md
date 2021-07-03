# Emby pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/emby.svg)](https://dash.yunohost.org/appci/app/emby) ![](https://ci-apps.yunohost.org/ci/badges/emby.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/emby.maintain.svg)  
[![Installer Emby avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=emby)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Emby rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Vos médias personnels sur n'importe quel appareil

**Version incluse :** 4.6.4.0~ynh1

**Démo :** https://demo.example.com

## Captures d'écran

![](./doc/screenshots/screenshot.png)

## Documentations et ressources

* Site officiel de l'app : https://emby.media/
* Documentation officielle utilisateur : https://yunohost.org/apps
* Documentation officielle de l'admin : https://support.emby.media/support/home
* Dépôt de code officiel de l'app : https://github.com/MediaBrowser/Emby
* Documentation YunoHost pour cette app : https://yunohost.org/app_emby
* Signaler un bug : https://github.com/YunoHost-Apps/emby_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/emby_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/emby_ynh/tree/testing --debug
ou
sudo yunohost app upgrade emby -u https://github.com/YunoHost-Apps/emby_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps