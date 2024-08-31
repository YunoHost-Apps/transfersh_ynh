<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Transfer.sh pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/transfersh.svg)](https://ci-apps.yunohost.org/ci/apps/transfersh/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/transfersh.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/transfersh.maintain.svg)

[![Installer Transfer.sh avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=transfersh)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Transfer.sh rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Partage de fichiers simple et rapide depuis la ligne de commande. Ce code contient le serveur avec tout ce dont vous avez besoin pour créer votre propre instance.
Transfer.sh prend actuellement en charge les fournisseurs Amazon S3, Google Drive, Storj et le système de fichiers local (local).

### Caractéristiques

- Conçu pour être utilisé avec un shell
- Partager des fichiers avec une URL
- Téléchargement illimité
- Fichiers stockés pour toujours
- Chiffrez vos fichiers
- Prévisualisez vos fichiers dans le navigateur

**Version incluse :** 1.6.1~ynh2

## Captures d’écran

![Capture d’écran de Transfer.sh](./doc/screenshots/transfer.sh-about.jpg)

## Documentations et ressources

- Site officiel de l’app : <https://transfer.sh/>
- Documentation officielle de l’admin : <https://github.com/dutchcoders/transfer.sh/>
- Dépôt de code officiel de l’app : <https://github.com/dutchcoders/transfer.sh>
- YunoHost Store : <https://apps.yunohost.org/app/transfersh>
- Signaler un bug : <https://github.com/YunoHost-Apps/transfersh_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/transfersh_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/transfersh_ynh/tree/testing --debug
ou
sudo yunohost app upgrade transfersh -u https://github.com/YunoHost-Apps/transfersh_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
