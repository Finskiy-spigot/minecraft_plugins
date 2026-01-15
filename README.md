# LdRestart

Автоматический перезапуск сервера Minecraft с BossBar и таймером.

## Особенности

- Автоперезапуск по расписанию (по часовой зоне, например МСК)
- BossBar и титлы с обратным отсчётом
- Возможность остановить рестарт командой `/rs stop`
- Возможность перезапустить конфиг командой `/rs reload`
- Конфигурируемые цвета и тексты

## Установка

1. Скачай `LdRestart.jar` и помести в папку `plugins` на сервере.
2. Перезапусти сервер, чтобы сгенерировался конфиг `config.yml`.

## Настройка

- restart_settings:
  - title:
    - name: "Рестарт"
    - sub_title: "через %time% секунд"
    - fadeIn: 5
    - stay: 20
    - fadeOut: 5
  - bossBar:
    - name: "Рестарт через %time% секунд"
    - barColor: RED
    - barStyle: SOLID

- auto_restart:
  - enabled: true
  - time_to_restart: 60 #seconds
  - tz: Europe/Moscow
  - time:
    - 12:00
    - "15:55"

#   TIMEZONE
Europe/Moscow
Europe/London
Europe/Paris
Europe/Berlin
Europe/Rome
Europe/Madrid
Europe/Kiev
Europe/Istanbul
Europe/Stockholm
Europe/Warsaw
Asia/Tokyo
Asia/Seoul
Asia/Shanghai
Asia/Hong_Kong
Asia/Singapore
Asia/Dubai
Asia/Jerusalem
Asia/Kolkata
Asia/Bangkok
Asia/Muscat
America/New_York
America/Chicago
America/Denver
America/Los_Angeles
America/Sao_Paulo
America/Mexico_City
America/Caracas
America/Argentina/Buenos_Aires
America/Anchorage
America/Phoenix
Africa/Cairo
Africa/Johannesburg
Africa/Lagos
Africa/Nairobi
Africa/Algiers
Australia/Sydney
Australia/Melbourne
Australia/Brisbane
Pacific/Auckland
Pacific/Fiji
