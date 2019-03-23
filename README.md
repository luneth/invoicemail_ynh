# InvoicePlane for YunoHost

[![Integration level](https://dash.yunohost.org/integration/REPLACEBYYOURAPP.svg)](https://dash.yunohost.org/appci/app/invoice)  
[![Install REPLACEBYYOURAPP with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=invoiceplane_ynh)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allow you to install InvoicePlane quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
Since the start of the project in 2014, InvoicePlane evolved into a software that is used world wide. However, it is
still developed in our free time, as a hobby. We do your best to fulfill any legal requirements but please note that we
cannot make sure that the app is working 100% correct. Also, due to the fact that InvoicePlane is a free and open
source software without an income, there are no professional audits of the app yet.

**Shipped version:** 1.5.9

## Screenshots

![](Link to an screenshot for this app)

## Demo

* https://invoiceplane.com/demo

## Configuration

How to configure this app: by an admin panel, a plain file with SSH, or any other way.

## Documentation

 * Official documentation: Link to the official documentation of this app
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-users support

Are LDAP and HTTP auth supported?
Can the app be used by multiple users?

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/REPLACEBYYOURAPP%20%28Community%29.svg)](https://ci-apps.yunohost.org/ci/apps/invoiceplane_ynh/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/REPLACEBYYOURAPP%20%28Community%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/invoiceplane_ynh/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/ci/logs/REPLACEBYYOURAPP%20%28Community%29.svg)](https://ci-stretch.nohost.me/ci/apps/invoiceplane_ynh/)

## Limitations

* Any known limitations.

## Additional information

* Other information you would add about this application

**More information on the documentation page:**  
https://yunohost.org/packaging_apps

## Links

 * Report a bug: https://github.com/YunoHost-Apps/invoiceplane_ynh/issues
 * App website: Link to the official website of this app
 * YunoHost website: https://yunohost.org/

---

Developers info
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/invoiceplane_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/invoiceplane_ynh/tree/testing --debug
or
sudo yunohost app upgrade invoiceplane_ynh -u https://github.com/YunoHost-Apps/invoiceplane_ynh/tree/testing --debug
```
