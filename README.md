# TG-Monitor Repository Overview

## Core

- [tgm-servicelocator](https://github.com/TG-Monitor/tgm-servicelocator)
- [tgm-entities](https://github.com/TG-Monitor/tgm-entities)
- [tgm-monitor](https://github.com/TG-Monitor/tgm-monitor)
- [tgm-monitor-facade](https://github.com/TG-Monitor/tgm-monitor-facade)
- [tgm-backend](https://github.com/TG-Monitor/tgm-backend)
- [tgm-telegram](https://github.com/TG-Monitor/tgm-telegram)
- [tgm-matching](https://github.com/TG-Monitor/tgm-matching)
- [tgm-notification](https://github.com/TG-Monitor/tgm-notification)
- [tgm-servicelocator-instances](https://github.com/TG-Monitor/tgm-servicelocator-instances)

## CLI Application

- [tgmc-cli](https://github.com/TG-Monitor/tgmc-cli)
- [tgmc-main](https://github.com/TG-Monitor/tgmc-main)
- [app-c-dist](https://github.com/TG-Monitor/app-c-dist)
- [app-c-docker](https://github.com/TG-Monitor/app-c-docker)
- [app-c-doc](https://github.com/TG-Monitor/app-c-doc)

## Detached CLI Application

- [tgmcd-rabbitmq-listener](https://github.com/TG-Monitor/tgmcd-rabbitmq-listener)
- [tgmcd-rabbitmq-monitor-facade](https://github.com/TG-Monitor/tgmcd-rabbitmq-monitor-facade)
- [tgmcd-main-monitor](https://github.com/TG-Monitor/tgmcd-main-monitor)
- [tgmcd-main-cli](https://github.com/TG-Monitor/tgmcd-main-cli)
- [app-dc-monitor-dist](https://github.com/TG-Monitor/app-dc-monitor-dist)
- [app-dc-cli-dist](https://github.com/TG-Monitor/app-dc-cli-dist)
- [app-dc-docker](https://github.com/TG-Monitor/app-dc-docker)
- [app-dc-doc](https://github.com/TG-Monitor/app-dc-doc)

## Comments

### Repository Naming

- `tgm-*`: core component
- `tgm<X>-*`: application-specific component, where `<X>` is the application identifier (see below)
- `app-<X>-*`: application-level repository (distribution package, Dockerfile, documentation, etc.), where `<X>` is the application identifier

### Application Identifiers

- `c`: CLI Application
- `dc`: Detached CLI Application

