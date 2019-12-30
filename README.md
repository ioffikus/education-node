# Описание задачи
Необходимо создаь сервис (или набор сервисов) реализующих API с функционалом: регистрации / авторизации пользователей, поиска картинок в flickr.com и сохранение запросов пользователей осуществляемых через сервис

# Функционал
- Регистрация
- Авторизация
- Запрос на получение данных с https://www.flickr.com/ по поисковому запросу с пагинацией
- Получение истории запросов пользователя
- Получение истории запросов всех польхователей

# Реализация
## Что не нужно делать?
- это обучающее задание, предполагает реализацию функционала задания в стадии рабочего прототипа, не нужно делать идеальное готовое production-ready решение
- задание расчитано нe более чем на 16 часов, если у вас оно занимает больше времени или у вас есть вопросы по описанным в данном документе концепциям или самому заданию - рекомендуем ознакомиться со списком литературы внизу данного документа и только после этого поэтапно приступать к реализации
- задание расчитано на разработчиков разного уровня, мы чётко понимаем что код junior разработчика и код senior разработчика отличается и при проверке задания учитываем уровень разработчика, не нужно доводить всё до идеала, делайте так как считаете нужным, мы с удовольствием обсудим вашу реализацию

## Язык реализации
- TypeScript (https://www.typescriptlang.org/)
- возможно использование минимального набора JS файлов для конфигурирования

## Среда разработки
- VSCode (https://code.visualstudio.com/)
- WebStorm (https://www.jetbrains.com/ru-ru/webstorm/)
- sublime (https://www.sublimetext.com/)

## Проверка кода
- eslint (https://eslint.org/)

## Тесты
- jest (https://jestjs.io/)
- mocha (https://mochajs.org/)
- должны быть реализован минимальный набор тестов

## Работа с репозиторием
- git-flow (https://danielkummer.github.io/git-flow-cheatsheet/index.html)
- важно то как вы ведёте работу с репозиторием

## Допустимые фреймворки
- nest.js (https://nestjs.com/)
- moleculer.services (https://moleculer.services/)
- своя реализация микросервисов
- своя реализация монолита

## Допустимые ORM / Базы данных
- mongoose (https://mongoosejs.com/)
- sequelizejs (https://sequelize.org/)
- typeorm (https://typeorm.io)
- mongodb (https://www.mongodb.com/)
- postgresql (https://www.postgresql.org/)

## Какие готовые решения лучше использовать?
- допустимо использование https://github.com/flickr/flickr-sdk
- axios (https://github.com/axios/axios)
- got (https://github.com/sindresorhus/got)

## Docker
- проект должен запускаться в Docker на любой ОС
- по желанию можно настроить docker-compose

# Список литературы
## Основы
- https://www.typescriptlang.org/docs/home.html
- https://basarat.gitbooks.io/typescript/
- https://ota-solid.now.sh/

## node.js
### База
- https://nodejs.org/ru/docs/
- https://github.com/goldbergyoni/nodebestpractices
- https://github.com/ehmicky/cross-platform-node-guide
- https://www.joyent.com/node-js/production/design/errors
- https://nodesource.com/blog/understanding-the-nodejs-event-loop/
- https://www.manning.com/books/express-in-action
  
### package.json
- https://habr.com/ru/company/ruvds/blog/423703/
### node.js awesome
- https://github.com/sindresorhus/awesome-nodejs

## REST API
- https://medium.com/@andr.ivas12/rest-%D0%BF%D1%80%D0%BE%D1%81%D1%82%D1%8B%D0%BC-%D1%8F%D0%B7%D1%8B%D0%BA%D0%BE%D0%BC-90a0bca0bc78
- http://www.restapitutorial.ru/

## GraphQL
- https://graphql.org/graphql-js/

## Микросервисы
- https://medium.com/webbdev/ms-b31365aa072e

