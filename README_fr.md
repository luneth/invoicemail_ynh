# App exemple pour YunoHost

[![Integration level](https://dash.yunohost.org/integration/invoiceplane_ynh.svg)](https://dash.yunohost.org/appci/app/invoice)  
[![Install invoiceplane with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=invoiceplane_ynh)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer InvoicePlane rapidement et simplement sur un serveur Yunohost.  
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble
Depuis le debut du projet en 2014, InvoicePlane a evolue en un logiciel utilise dans le monde entier. Cela dit, il est et reste developpe durant notre temps libre, comme hobby. Nous faisons de notre mieux a fin d'assouvir les besoins legaux, mais s'il vous plait veuillez noter que nous ne pouvons garantir que cette application fonctionne 100% correctement. Aussi,du fait que Invoiceplane est un logiciel libre et opensource sans revenus, il n'y a pas encore d'audit professionnel de l'application.

**Version incluse:** 1.5.9

## Captures d'écran

![](https://invoiceplane.com/assets/img/preview.jpg)

## Démo

* [Démo officielle](https://invoiceplane.com/demo)

## Configuration

Comment configurer cette application: via le panneau d'administration, un fichier brut en SSH ou tout autre moyen.

## Documentation

 * Documentation officielle: Lien vers la documentation officielle de cette application
 * Documentation YunoHost: Si une documentation spécifique est nécessaire, n'hésitez pas à contribuer.

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateurs

L'authentification LDAP et HTTP est-elle prise en charge?
L'application peut-elle être utilisée par plusieurs utilisateurs?

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/REPLACEBYYOURAPP%20%28Community%29.svg)](https://ci-apps.yunohost.org/ci/apps/invoiceplane_ynh/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/REPLACEBYYOURAPP%20%28Community%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/invoiceplane_ynh/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/ci/logs/REPLACEBYYOURAPP%20%28Community%29.svg)](https://ci-stretch.nohost.me/ci/apps/invoiceplane_ynh/)

## Limitations

* Limitations connues.

## Informations additionnelles

* Autres informations à ajouter sur cette application

**Plus d'informations sur la page de documentation:**  
https://yunohost.org/packaging_apps

## Links

 * Signaler un bug: https://github.com/YunoHost-Apps/invoiceplane_ynh/issues
 * Site de l'application: Lien vers le site officiel de cette application
 * Site web YunoHost: https://yunohost.org/

---

Informations pour les développeurs
----------------

**Seulement si vous voulez utiliser une branche de test pour le codage, au lieu de fusionner directement dans la banche principale.**
Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/invoiceplane_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/invoiceplane_ynh/tree/testing --debug
ou
sudo yunohost app upgrade REPLACEBYYOURAPP -u https://github.com/YunoHost-Apps/invoiceplane_ynh/tree/testing --debug
```
