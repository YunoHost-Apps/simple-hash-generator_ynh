# Simple-Hash-Generator pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/simple-hash-generator.svg)](https://dash.yunohost.org/appci/app/simple-hash-generator) ![](https://ci-apps.yunohost.org/ci/badges/simple-hash-generator.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/simple-hash-generator.maintain.svg)  
[![Installer Simple-Hash-Generator avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=simple-hash-generator)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Simple-Hash-Generator rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

A simple hash generator utilizing a collection of popular and useful hash functions


**Version incluse :** 1.0~ynh1

**Démo :** https://prizz.github.io/Simple-Hash-Generator/

## Captures d'écran

![](./doc/screenshots/example.jpg)

## Avertissements / informations importantes

# Disclaimer

All hashing is done directly in the browser. Your data is not sent to any server, ever. If you are skeptical, which I respect, I recommend [downloading the latest release here](https://github.com/pRizz/Simple-Hash-Generator/releases), turning off your internet, unzip the release, open index.html, check out the network debugger, and see that hashing still works. Or if you are a developer, you can audit the [source code here](https://github.com/pRizz/Simple-Hash-Generator).

# About the Author

This project was originally created by Peter Ryszkiewicz ([pRizz@GitHub](https://github.com/pRizz)), software engineer in Chicago, IL.

# About the Project

This project is hosted on GitHub at https://github.com/pRizz/Simple-Hash-Generator under the MIT license.

## Documentations et ressources

* Site officiel de l'app : https://prizz.github.io/Simple-Hash-Generator/
* Dépôt de code officiel de l'app : https://github.com/pRizz/Simple-Hash-Generator
* Documentation YunoHost pour cette app : https://yunohost.org/app_simple-hash-generator
* Signaler un bug : https://github.com/YunoHost-Apps/simple-hash-generator_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/simple-hash-generator_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/simple-hash-generator_ynh/tree/testing --debug
ou
sudo yunohost app upgrade simple-hash-generator -u https://github.com/YunoHost-Apps/simple-hash-generator_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps