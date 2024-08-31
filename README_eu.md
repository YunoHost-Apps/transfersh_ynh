<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Transfer.sh YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/transfersh.svg)](https://ci-apps.yunohost.org/ci/apps/transfersh/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/transfersh.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/transfersh.maintain.svg)

[![Instalatu Transfer.sh YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=transfersh)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Transfer.sh YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Easy and fast file sharing from the command-line. This code contains the server with everything you need to create your own instance.
Transfer.sh currently supports the s3 (Amazon S3), gdrive (Google Drive), storj (Storj) providers, and local file system (local).

### Features

- Made for use with shell
- Share files with a URL
- Unlimited upload
- Files stored forever
- Encrypt your files
- Preview your files in the browser


**Paketatutako bertsioa:** 1.6.1~ynh2

## Pantaila-argazkiak

![Transfer.sh(r)en pantaila-argazkia](./doc/screenshots/transfer.sh-about.jpg)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://transfer.sh/>
- Administratzaileen dokumentazio ofiziala: <https://github.com/dutchcoders/transfer.sh/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/dutchcoders/transfer.sh>
- YunoHost Denda: <https://apps.yunohost.org/app/transfersh>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/transfersh_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/transfersh_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/transfersh_ynh/tree/testing --debug
edo
sudo yunohost app upgrade transfersh -u https://github.com/YunoHost-Apps/transfersh_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
