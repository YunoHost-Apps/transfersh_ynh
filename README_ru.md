<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Transfer.sh для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/transfersh)](https://ci-apps.yunohost.org/ci/apps/transfersh/)
![Состояние работы](https://apps.yunohost.org/badge/state/transfersh)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/transfersh)

[![Установите Transfer.sh с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=transfersh)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Transfer.sh быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Easy and fast file sharing from the command-line. This code contains the server with everything you need to create your own instance.
Transfer.sh currently supports the s3 (Amazon S3), gdrive (Google Drive), storj (Storj) providers, and local file system (local).

### Features

- Made for use with shell
- Share files with a URL
- Unlimited upload
- Files stored forever
- Encrypt your files
- Preview your files in the browser


**Поставляемая версия:** 1.6.1~ynh2

## Снимки экрана

![Снимок экрана Transfer.sh](./doc/screenshots/transfer.sh-about.jpg)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://transfer.sh/>
- Официальная документация администратора: <https://github.com/dutchcoders/transfer.sh/>
- Репозиторий кода главной ветки приложения: <https://github.com/dutchcoders/transfer.sh>
- Магазин YunoHost: <https://apps.yunohost.org/app/transfersh>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/transfersh_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/transfersh_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/transfersh_ynh/tree/testing --debug
или
sudo yunohost app upgrade transfersh -u https://github.com/YunoHost-Apps/transfersh_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
