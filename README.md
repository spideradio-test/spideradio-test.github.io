# Тестовый магазин для запуска hermione-тестов
Урл магазина // todo

Для редактирования магазина нужно:
1. Внести изменения в [feed.json](/feed.json) (руками или с помощью [updateJsonFeed](/tools/updateJsonFeed.js))
1. Сгенерировать `YML` фид
1. Опубликовать полученный фид

## Генерация YML фида из json
После редактирования [feed.json](/feed.json) нужно запустить npm скрипт
```bash
npm run build-feed
```
который сгенерирует `YML` фид из json файла. Фид будет лежать в `./docs/feed.xml`

## Публикация YML фида
```bash
todo
```