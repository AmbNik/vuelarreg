# renovation-studio
# Инструкция по разворачиванию фронтовой части

## Установка пакетов 

Если вы уже [подняли репозиторий](../README.md#подготовка-и-настройка-репозитория) через `npm i` в корневой папке до этого, дополнительная установка пакетов не требуется, т.к. фронтовая часть находится в пространстве монорепозитория 

Т.к. сама фронтовая часть находится в пространстве монорепозитория, необходимо при первой установке ставить пакеты исключительно в пространстве самого репозитория (НЕ ПАПКИ `frontend`, иначе не поднимется husky)

После этого перейдите в папку `frontend`

```sh
cd ./frontend
```

## Деплой

Актуальная информация по деплою фронта находится [в корневом `README.md` проекта](../README.md#деплои-фронта)

## Полезные команды (выполнять в папке frontend)

### HMR и локальный девсервер

```sh
npm run dev
```

### Сборка проекта (требуется для деплоя и разворачивании на хостинге)

```sh
npm run build
```

### Линт файлов через [ESLint](https://eslint.org/)

```sh
npm run lint
```