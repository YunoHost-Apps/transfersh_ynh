<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Transfer.sh untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/transfersh.svg)](https://ci-apps.yunohost.org/ci/apps/transfersh/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/transfersh.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/transfersh.maintain.svg)

[![Pasang Transfer.sh dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=transfersh)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Transfer.sh secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Easy and fast file sharing from the command-line. This code contains the server with everything you need to create your own instance.
Transfer.sh currently supports the s3 (Amazon S3), gdrive (Google Drive), storj (Storj) providers, and local file system (local).

### Features

- Made for use with shell
- Share files with a URL
- Unlimited upload
- Files stored forever
- Encrypt your files
- Preview your files in the browser


**Versi terkirim:** 1.6.1~ynh1

## Tangkapan Layar

![Tangkapan Layar pada Transfer.sh](./doc/screenshots/transfer.sh-about.jpg)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://transfer.sh/>
- Dokumentasi admin resmi: <https://github.com/dutchcoders/transfer.sh/>
- Depot kode aplikasi hulu: <https://github.com/dutchcoders/transfer.sh>
- Gudang YunoHost: <https://apps.yunohost.org/app/transfersh>
- Laporkan bug: <https://github.com/YunoHost-Apps/transfersh_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/transfersh_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/transfersh_ynh/tree/testing --debug
atau
sudo yunohost app upgrade transfersh -u https://github.com/YunoHost-Apps/transfersh_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
