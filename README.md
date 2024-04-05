# WA-CLIENT
#### Менеджер сообщений мессенджера WhatsApp
![Info-Graphics](./documentation/image.png)

> Приложение при получении сообщения из *мессенджера*, преобразовывает в валидный формат для *обозначенного сервера*, и помещает в очередь отправки на эндпоинт этого сервера.
Так же обьявлен эндпоинт самого приложения, по которому с обозначенного сервера могут приходить сообщения. При их получении, приложение преобразовывает в валидный для *мессенджера* формат, и помещает в очередь отправки до мессенджера.

## Оглавление
- [Работа приложения](#работа-приложения)
- [Ключевые зависимости](#ключевые-зависимости)
- [Запуск](#запуск)
- [Настройки](#настройки)
- [API](#api)
- [База данных / MongoDB](#база-данных--mongodb)
- [Архитектура](#архитектура)
- [Памятка разработчику](#памятка-разработчику)
  - [Локальный запуск](#локальный-запуск)
  - [Запуск через сборку проекта](#запуск-через-сборку-проекта)
- [Термины](#термины)

## Работа приложения

Основная задача приложения заключена в менеджменте сообщений из WhatsApp до выделенного сервера и от выделенного сервера в WhatsApp.

## Ключевые зависимости
[![NodeJS](https://img.shields.io/badge/NODEJS-16.16-6DA55F?style=for-the-badge&logo=node.js&logoColor=6DA55F)](https://nodejs.org/en/blog/release/v16.16.0 "Node JS") [![npm](https://img.shields.io/badge/Npm-7-red?style=for-the-badge&logo=npm&logoColor=red) ](https://www.npmjs.com/package/npm/v/7.0.0 "NPM")

[![MongoDB](https://img.shields.io/badge/MONGODB->=5.0.9-589636?style=for-the-badge&logo=mongodb&logoColor=589636)](https://www.mongodb.com/docs/manual/release-notes/5.0/ "MongoDB")

[![Baileys](https://img.shields.io/badge/@whiskeysockets/baileys-6.6.0-25d366?style=for-the-badge&logo=whatsapp&logoColor=25d366)](https://github.com/WhiskeySockets/Baileys "Страница библиотеки Baileys")
