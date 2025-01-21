<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Transfer.sh

[![集成程度](https://apps.yunohost.org/badge/integration/transfersh)](https://ci-apps.yunohost.org/ci/apps/transfersh/)
![工作状态](https://apps.yunohost.org/badge/state/transfersh)
![维护状态](https://apps.yunohost.org/badge/maintained/transfersh)

[![使用 YunoHost 安装 Transfer.sh](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=transfersh)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Transfer.sh。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Easy and fast file sharing from the command-line. This code contains the server with everything you need to create your own instance.
Transfer.sh currently supports the s3 (Amazon S3), gdrive (Google Drive), storj (Storj) providers, and local file system (local).

### Features

- Made for use with shell
- Share files with a URL
- Unlimited upload
- Files stored forever
- Encrypt your files
- Preview your files in the browser


**分发版本：** 1.6.1~ynh2

## 截图

![Transfer.sh 的截图](./doc/screenshots/transfer.sh-about.jpg)

## 文档与资源

- 官方应用网站： <https://transfer.sh/>
- 官方管理文档： <https://github.com/dutchcoders/transfer.sh/>
- 上游应用代码库： <https://github.com/dutchcoders/transfer.sh>
- YunoHost 商店： <https://apps.yunohost.org/app/transfersh>
- 报告 bug： <https://github.com/YunoHost-Apps/transfersh_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/transfersh_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/transfersh_ynh/tree/testing --debug
或
sudo yunohost app upgrade transfersh -u https://github.com/YunoHost-Apps/transfersh_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
