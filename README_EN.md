# Emby Telerising EasyEPG DockerPack for UGREEN NAS

[![Compose](https://github.com/Railsimulatornet/UGREEN-NAS-Emby-Telerising-EasyEPG-DockerPack/actions/workflows/compose-validation.yml/badge.svg?branch=main)](https://github.com/Railsimulatornet/UGREEN-NAS-Emby-Telerising-EasyEPG-DockerPack/actions/workflows/compose-validation.yml)

[Deutsch](README.md)

This repository provides a ready-to-use Docker project for **UGREEN NAS (UGOS Pro)**:
**Emby Media Server + SWAG (reverse proxy) + EasyEPG + Telerising**.

## Contents

- **de/**: German project + German PDF manual
- **en/**: English project + English PDF manual
- [Releases](https://github.com/Railsimulatornet/UGREEN-NAS-Emby-Telerising-EasyEPG-DockerPack/releases/latest): ready-to-use ZIP files (DE and EN)

## Quick start (UGREEN Docker app)

1. Download the ZIP from the [latest release](https://github.com/Railsimulatornet/UGREEN-NAS-Emby-Telerising-EasyEPG-DockerPack/releases/latest):
   - **DE**: file ending in `_de.zip`
   - **EN**: file ending in `_en.zip`

2. Extract into your Docker directory on the NAS.

3. Edit `embyserver/.env` in the extracted package (paths, SWAG domain, UID/GID, ports).

4. Import the `embyserver` folder in the UGREEN Docker app and start the project.

## Documentation

- German: `de/EmbyServer_Handbuch_DE_v1.pdf`
- English: `en/EmbyServer_Handbuch_EN_v1.pdf`
