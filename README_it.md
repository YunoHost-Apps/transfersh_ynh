<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# Transfer.sh per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/transfersh.svg)](https://dash.yunohost.org/appci/app/transfersh) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/transfersh.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/transfersh.maintain.svg)

[![Installa Transfer.sh con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=transfersh)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare Transfer.sh su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

Easy and fast file sharing from the command-line. This code contains the server with everything you need to create your own instance.
Transfer.sh currently supports the s3 (Amazon S3), gdrive (Google Drive), storj (Storj) providers, and local file system (local).

### Features

- Made for use with shell
- Share files with a URL
- Unlimited upload
- Files stored forever
- Encrypt your files
- Preview your files in the browser


**Versione pubblicata:** 1.6.1~ynh1

## Screenshot

![Screenshot di Transfer.sh](./doc/screenshots/transfer.sh-about.jpg)

## Documentazione e risorse

- Sito web ufficiale dell’app: <https://transfer.sh/>
- Documentazione ufficiale per gli amministratori: <https://github.com/dutchcoders/transfer.sh/>
- Repository upstream del codice dell’app: <https://github.com/dutchcoders/transfer.sh>
- Store di YunoHost: <https://apps.yunohost.org/app/transfersh>
- Segnala un problema: <https://github.com/YunoHost-Apps/transfersh_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/transfersh_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/transfersh_ynh/tree/testing --debug
o
sudo yunohost app upgrade transfersh -u https://github.com/YunoHost-Apps/transfersh_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
