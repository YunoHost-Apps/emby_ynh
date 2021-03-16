# Emby for YunoHost

[![Integration level](https://dash.yunohost.org/integration/emby.svg)](https://dash.yunohost.org/appci/app/emby) ![](https://ci-apps.yunohost.org/ci/badges/emby.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/emby.maintain.svg)  
[![Install emby with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=emby)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install emby quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Quick description of this app.

**Shipped version:** 4.5.4.0

## Screenshots

![](https://raw.githubusercontent.com/MediaBrowser/Emby.Resources/master/apps/html5.png)

## Demo

* [Official demo](Link to a demo site for this app.)

## Configuration

How to configure this app: From an admin panel, a plain file with SSH, or any other way.

## Documentation

 * Official documentation: Link to the official documentation of this app
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

Are LDAP and HTTP auth supported?
Can the app be used by multiple users?

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/emby%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/emby/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/emby%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/emby/)

## Limitations

* Any known limitations.

## Additional information

* Other info you would like to add about this app.

**More info on the documentation page:**  
https://yunohost.org/packaging_apps

## Links

 * Report a bug: https://github.com/YunoHost-Apps/emby_ynh/issues
 * App website: https://emby.media/
 * Upstream app repository: Link to the official repository of the upstream app.
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/emby_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/emby_ynh/tree/testing --debug
or
sudo yunohost app upgrade emby -u https://github.com/YunoHost-Apps/emby_ynh/tree/testing --debug
```






Emby Server

**Shipped version:** 4.4.2.0

- [Yunohost project](https://yunohost.org)
- [Emby website](https://emby.media/)

![](https://emby.media/resources/logowhite_1881.png)


[![Install Emby with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=emby)


### Installing guide

 App can be installed by YunoHost **admin web-interface** or by **running following command**:

         $ sudo yunohost app install https://github.com/YunoHost-Apps/emby_ynh

 
### Upgrade this package:

        $ sudo yunohost app upgrade embyserver -u https://github.com/YunoHost-Apps/emby_ynh

