# Сборка
Репозиторий для быстрого и одновременного запуска всех сервисов на одном устройстве.

## Установка
Клонирование с подгрузкой подмодулей:
```shell
git clone –recurse-submodules  https://github.com/myna-labs-test/backend-bundle
```

## Мигрирование бд
Необходимо перейти в `migrations` и следовать [инструкциям](migrations/README.md)
## Запуск Client API
Необходимо перейти в `client` и следовать [инструкциям](client/README.md)
## Запуск Character API
Необходимо перейти в `characters` и следовать [инструкциям](characters/README.md)
## Запуск телеграм бота
Необходимо перейти в `bot` и следовать [инструкциям](bot/README.md)