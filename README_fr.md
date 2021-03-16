# Emby pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/emby.svg)](https://dash.yunohost.org/appci/app/emby) ![](https://ci-apps.yunohost.org/ci/badges/emby.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/emby.maintain.svg)  
[![Installer Emby avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=emby)

*[Read this readme in english.](./README.md)* 

> *This package allows you to install emby quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Vue d'ensemble
Quick description of this app.

**Version incluse :**  4.5.4.0

## Captures d'écran

![](https://raw.githubusercontent.com/MediaBrowser/Emby.Resources/master/apps/html5.png)

## Démo

* [Démo officielle](Link to a demo site for this app.)

## Configuration

Comment configurer cette application : via le panneau d'administration, un fichier brut en SSH ou tout autre moyen.

## Documentation

* L'authentification LDAP et HTTP est-elle prise en charge ?
* L'application peut-elle être utilisée par plusieurs utilisateurs ?

## YunoHost specific features

#### Multi-user support

 * Documentation officielle : https://support.emby.media/support/home
 * Documentation YunoHost : Si une documentation spécifique est nécessaire, n'hésitez pas à contribuer.

#### Support multi-utilisateur

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/emby%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/emby/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/emby%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/emby/)

## Limitations

* Any known limitations.

## Additional information

* Autres informations que vous souhaitez ajouter sur cette application.

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/emby_ynh/issues
 * Site de l'application : https://emby.media/
 * Dépôt de l'application principale : Link to the official repository of the upstream app.
 * Site web YunoHost : https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/emby_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/emby_ynh/tree/testing --debug
or
sudo yunohost app upgrade emby -u https://github.com/YunoHost-Apps/emby_ynh/tree/testing --debug
```
