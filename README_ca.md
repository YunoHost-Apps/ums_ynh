<!--
N.B.: Aquest README ha estat generat automàticament per <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NO s'ha de modificar manualment.
-->

# Universal Media Server per YunoHost

[![Nivell d'integració](https://apps.yunohost.org/badge/integration/ums)](https://ci-apps.yunohost.org/ci/apps/ums/)
![Estat de funcionament](https://apps.yunohost.org/badge/state/ums)
![Estat de manteniment](https://apps.yunohost.org/badge/maintained/ums)

[![Instal·la Universal Media Server amb YunoHosth](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ums)

*[Llegeix aquest README en altres idiomes.](./ALL_README.md)*

> *Aquest paquet et permet instal·lar Universal Media Server de forma ràpida i senzilla en un servidor YunoHost.*  
> *Si no tens YunoHost, consulta [la guia](https://yunohost.org/install) per saber com instal·lar-lo.*

## Visió general

Universal Media Server is a DLNA-compliant UPnP Media Server. It is capable of sharing video, audio and images between most modern devices.
The program streams or transcodes many different media formats with little or no configuration. It is powered by FFmpeg, MediaInfo, OpenSubtitles, Crowdin, MEncoder, tsMuxeR, AviSynth, VLC and more, which combine to offer support for a wide range of media formats.

**Versió inclosa:** 14.11.0~ynh1

## Captures de pantalla

![Captures de pantalla de Universal Media Server](./doc/screenshots/screenshot.png)

## Documentació i recursos

- Lloc web oficial de l'aplicació: <www.universalmediaserver.com>
- Documentació oficial per l'administrador: <https://github.com/UniversalMediaServer/UniversalMediaServer/wiki>
- Repositori oficial del codi de l'aplicació: <https://github.com/UniversalMediaServer/UniversalMediaServer>
- Botiga YunoHost: <https://apps.yunohost.org/app/ums>
- Reportar un error: <https://github.com/YunoHost-Apps/ums_ynh/issues>

## Informació per a desenvolupadors

Envieu les pull request a la [branca `testing`](https://github.com/YunoHost-Apps/ums_ynh/tree/testing).

Per provar la branca `testing`, procedir com descrit a continuació:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ums_ynh/tree/testing --debug
o
sudo yunohost app upgrade ums -u https://github.com/YunoHost-Apps/ums_ynh/tree/testing --debug
```

**Més informació sobre l'empaquetatge d'aplicacions:** <https://yunohost.org/packaging_apps>
