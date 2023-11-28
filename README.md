<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# GitList for YunoHost

[![Integration level](https://dash.yunohost.org/integration/gitlist.svg)](https://dash.yunohost.org/appci/app/gitlist) ![Working status](https://ci-apps.yunohost.org/ci/badges/gitlist.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/gitlist.maintain.svg)

[![Install GitList with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gitlist)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install GitList quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

GitList is an elegant and modern web interface for interacting with multiple git repositories. It allows you to browse repositories using your favorite browser, viewing files under different revisions, commit history, diffs. It also generates RSS/Atom feeds for each repository, allowing you to stay up-to-date with the latest changes anytime, anywhere.

### Features

- Multiple repository support
- Multiple branch support
- Multiple tag support
- Commit history, blame, diff
- RSS/Atom feeds
- Syntax highlighting via CodeMirror or Ace
- Repository statistics


**Shipped version:** 2.0.0~ynh4

## Screenshots

![Screenshot of GitList](./doc/screenshots/screenshot.png)

## Documentation and resources

* Official app website: <https://gitlist.org/>
* Official admin documentation: <https://github.com/klaussilveira/gitlist/wiki>
* Upstream app code repository: <https://github.com/klaussilveira/gitlist>
* YunoHost Store: <https://apps.yunohost.org/app/gitlist>
* Report a bug: <https://github.com/YunoHost-Apps/gitlist_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/gitlist_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/gitlist_ynh/tree/testing --debug
or
sudo yunohost app upgrade gitlist -u https://github.com/YunoHost-Apps/gitlist_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
