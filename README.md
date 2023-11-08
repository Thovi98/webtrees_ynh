<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Webtrees for YunoHost

[![Integration level](https://dash.yunohost.org/integration/webtrees.svg)](https://dash.yunohost.org/appci/app/webtrees) ![Working status](https://ci-apps.yunohost.org/ci/badges/webtrees.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/webtrees.maintain.svg)

[![Install Webtrees with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=webtrees)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Webtrees quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Webtrees allows you to view and edit your genealogy on your website. It has full editing capabilities, full privacy functions, and supports imedia such as photos and document images. As an online program, it fosters extended family participation and good ancestral recording habits, as it simplifies the process of collaborating with others working on your family lines. Your latest information is always on your web site and available for others to see, defined by viewing rules you set.

- It works from standard GEDCOM files, and is therefore compatible with every major desktop application.
- It aims to to be efficient and effective by using the right combination of third-party tools, design techniques and open standards.

**Note:** Its better to upgrade from the Webtrees admin panel when new version arrives.


**Shipped version:** 2.1.18~ynh2

**Demo:** https://dev.webtrees.net/demo-stable/index.php?route=%2Fdemo-stable%2Ftree%2Fdemo

## Screenshots

![Screenshot of Webtrees](./doc/screenshots/1200px-Webtrees.png)

## Documentation and resources

* Official app website: <https://www.webtrees.net>
* Official admin documentation: <https://wiki.webtrees.net>
* Upstream app code repository: <https://github.com/fisharebest/webtrees>
* YunoHost Store: <https://apps.yunohost.org/app/webtrees>
* Report a bug: <https://github.com/YunoHost-Apps/webtrees_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/webtrees_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/webtrees_ynh/tree/testing --debug
or
sudo yunohost app upgrade webtrees -u https://github.com/YunoHost-Apps/webtrees_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
