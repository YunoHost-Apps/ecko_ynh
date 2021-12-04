# Ecko pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/ecko.svg)](https://dash.yunohost.org/appci/app/ecko) ![](https://ci-apps.yunohost.org/ci/badges/ecko.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/ecko.maintain.svg)  
[![Installer Ecko avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ecko)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Ecko rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Fork dynamique du réseau social fédéré de Mastodon, créé en août 2021.

**Version incluse :** 2021.11.23~ynh1



## Avertissements / informations importantes

Ecko is beta software, and under active development. Use at your own risk!

* This app requires a dedicated domain or subdomain.
* The user chosen during the installation is created in Ecko with admin rights.
* LDAP authentication is activated. All YunoHost users can authenticate.
* Single sign-on doesn't work.

You may wish to close or limit registration for your instance of Ecko, so that the instance stays small. We invite you to block remote malicious instances from the administration interface. You can also add text on your home page.

## Documentations et ressources

* Site officiel de l'app : https://magicstone.dev
* Dépôt de code officiel de l'app : https://github.com/magicstone-dev/ecko
* Documentation YunoHost pour cette app : https://yunohost.org/app_ecko
* Signaler un bug : https://github.com/YunoHost-Apps/ecko_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/ecko_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/ecko_ynh/tree/testing --debug
ou
sudo yunohost app upgrade ecko -u https://github.com/YunoHost-Apps/ecko_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps