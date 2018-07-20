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
- [app-cli](https://github.com/TG-Monitor/app-cli)

## Detached CLI Application

- [tgmdc-rabbitmq-listener](https://github.com/TG-Monitor/tgmdc-rabbitmq-listener)
- [tgmdc-rabbitmq-monitor-facade](https://github.com/TG-Monitor/tgmdc-rabbitmq-monitor-facade)
- [tgmdc-main-monitor](https://github.com/TG-Monitor/tgmdc-main-monitor)
- [tgmdc-main-cli](https://github.com/TG-Monitor/tgmdc-main-cli)
- [app-detached-monitor](https://github.com/TG-Monitor/app-detached-monitor)
- [app-detached-cli](https://github.com/TG-Monitor/app-detached-cli)

## Comments

### Repository Naming

- `tgm-*`: core component
- `tgm<X>-*`: application-specific component, where `<X>` is the application identifier (see below)
- `app-*`: application bundle repository (executable, Dockerfile, documentation, etc.)

### Application Identifiers

- `c`: CLI Application
- `dc`: Detached CLI Application

