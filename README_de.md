<!--
N.B.: Diese README wurde automatisch von <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> generiert.
Sie darf NICHT von Hand bearbeitet werden.
-->

# Universal Media Server für YunoHost

[![Integrations-Level](https://apps.yunohost.org/badge/integration/ums)](https://ci-apps.yunohost.org/ci/apps/ums/)
![Funktionsstatus](https://apps.yunohost.org/badge/state/ums)
![Wartungsstatus](https://apps.yunohost.org/badge/maintained/ums)

[![Universal Media Server mit YunoHost installieren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ums)

*[Dieses README in anderen Sprachen lesen.](./ALL_README.md)*

> *Mit diesem Paket können Sie Universal Media Server schnell und einfach auf einem YunoHost-Server installieren.*  
> *Wenn Sie YunoHost nicht haben, lesen Sie bitte [die Anleitung](https://yunohost.org/install), um zu erfahren, wie Sie es installieren.*

## Übersicht

Universal Media Server is a DLNA-compliant UPnP Media Server. It is capable of sharing video, audio and images between most modern devices.
The program streams or transcodes many different media formats with little or no configuration. It is powered by FFmpeg, MediaInfo, OpenSubtitles, Crowdin, MEncoder, tsMuxeR, AviSynth, VLC and more, which combine to offer support for a wide range of media formats.

**Ausgelieferte Version:** 14.11.0~ynh1

## Bildschirmfotos

![Bildschirmfotos von Universal Media Server](./doc/screenshots/screenshot.png)

## Dokumentation und Ressourcen

- Offizielle Website der App: <www.universalmediaserver.com>
- Offizielle Verwaltungsdokumentation: <https://github.com/UniversalMediaServer/UniversalMediaServer/wiki>
- Upstream App Repository: <https://github.com/UniversalMediaServer/UniversalMediaServer>
- YunoHost-Shop: <https://apps.yunohost.org/app/ums>
- Einen Fehler melden: <https://github.com/YunoHost-Apps/ums_ynh/issues>

## Entwicklerinformationen

Bitte senden Sie Ihren Pull-Request an den [`testing` branch](https://github.com/YunoHost-Apps/ums_ynh/tree/testing).

Um den `testing` Branch auszuprobieren, gehen Sie bitte wie folgt vor:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ums_ynh/tree/testing --debug
oder
sudo yunohost app upgrade ums -u https://github.com/YunoHost-Apps/ums_ynh/tree/testing --debug
```

**Weitere Informationen zur App-Paketierung:** <https://yunohost.org/packaging_apps>
