<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Transfer.sh dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/transfersh)](https://ci-apps.yunohost.org/ci/apps/transfersh/)
![Status działania](https://apps.yunohost.org/badge/state/transfersh)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/transfersh)

[![Zainstaluj Transfer.sh z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=transfersh)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Transfer.sh na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

Easy and fast file sharing from the command-line. This code contains the server with everything you need to create your own instance.
Transfer.sh currently supports the s3 (Amazon S3), gdrive (Google Drive), storj (Storj) providers, and local file system (local).

### Features

- Made for use with shell
- Share files with a URL
- Unlimited upload
- Files stored forever
- Encrypt your files
- Preview your files in the browser


**Dostarczona wersja:** 1.6.1~ynh2

## Zrzuty ekranu

![Zrzut ekranu z Transfer.sh](./doc/screenshots/transfer.sh-about.jpg)

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://transfer.sh/>
- Oficjalna dokumentacja dla administratora: <https://github.com/dutchcoders/transfer.sh/>
- Repozytorium z kodem źródłowym: <https://github.com/dutchcoders/transfer.sh>
- Sklep YunoHost: <https://apps.yunohost.org/app/transfersh>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/transfersh_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/transfersh_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/transfersh_ynh/tree/testing --debug
lub
sudo yunohost app upgrade transfersh -u https://github.com/YunoHost-Apps/transfersh_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
