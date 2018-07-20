# TG-Monitor Repository Overview

## Core

- [tgm-servicelocator](https://github.com/TG-Monitor/tgm-servicelocator)
- [tgm-entities](https://github.com/TG-Monitor/tgm-entities)
- [tgm-monitor](https://github.com/TG-Monitor/tgm-monitor)
- [tgm-monitor-facade](https://github.com/TG-Monitor/tgm-monitor-facade)
- [tgm-backend](https://github.com/TG-Monitor/tgm-backend)
- [tgm-matching](https://github.com/TG-Monitor/tgm-matching)
- [tgm-telegram](https://github.com/TG-Monitor/tgm-telegram)
- [tgm-notification](https://github.com/TG-Monitor/tgm-notification)
- [tgm-servicelocator-instances](https://github.com/TG-Monitor/tgm-servicelocator-instances)

## CLI Application

- [tgmc-cli](https://github.com/TG-Monitor/tgmc-cli)
- [tgmc-main](https://github.com/TG-Monitor/tgmc-main)
- [app-dist-c](https://github.com/TG-Monitor/app-dist-c)
- [app-docker-c](https://github.com/TG-Monitor/app-docker-c)
- [app-doc-c](https://github.com/TG-Monitor/app-doc-c)

## Detached CLI Application

- [tgmcd-rabbitmq-listener](https://github.com/TG-Monitor/tgmcd-rabbitmq-listener)
- [tgmcd-rabbitmq-monitor-facade](https://github.com/TG-Monitor/tgmcd-rabbitmq-monitor-facade)
- [tgmcd-main-monitor](https://github.com/TG-Monitor/tgmcd-main-monitor)
- [tgmcd-main-cli](https://github.com/TG-Monitor/tgmcd-main-cli)
- [app-dist-cd-monitor](https://github.com/TG-Monitor/app-dist-cd-monitor)
- [app-dist-cd-cli](https://github.com/TG-Monitor/app-dist-cd-cli)
- [app-docker-cd](https://github.com/TG-Monitor/app-docker-cd)
- [app-doc-cd](https://github.com/TG-Monitor/app-doc-cd)

## Comments

### Repository Naming

- `tgm-*`: core component
- `tgm<X>-*`: application-specific component, where `<X>` is the application identifier (see below)
- `app-*`: application-level repository (distribution package, Dockerfile, documentation, etc.)

### Application Identifiers

- `c`: CLI Application
- `cd`: Detached CLI Application

