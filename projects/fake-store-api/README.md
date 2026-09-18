# Тестирование Fake Store API

## О проекте

Учебный проект по тестированию публичного REST API [Fake Store API](https://fakestoreapi.com). Проверены ресурсы `Products` и `Carts`, CRUD-операции, структура JSON-ответов и обработка некорректных данных.

## Покрытие

- получение списка объектов;
- получение объекта по идентификатору;
- создание, изменение и удаление объектов;
- проверка HTTP-статусов и `Content-Type`;
- проверка валидности JSON и структуры ответа;
- проверка идентификаторов в ответе;
- отправка пустого тела;
- отправка значений неверных типов.

## Инструменты

- Postman;
- JavaScript-тесты Postman;
- HTTP и JSON;
- cURL;
- Git и GitHub.

## Артефакты

- [Коллекция Products](postman/Fake-Store-API-Products.postman_collection.json)
- [Коллекция Carts](postman/Fake-Store-API-Carts.postman_collection.json)
- [Окружение Postman](postman/Fake-Store-API.postman_environment.json)
- [Результаты негативных проверок](test-results.md)
- [Баг-репорт: Products](bug-reports/BR-API-001-products-validation.md)
- [Баг-репорт: Carts](bug-reports/BR-API-002-carts-validation.md)

## Запуск коллекций

1. Импортировать окружение и обе коллекции в Postman.
2. Выбрать окружение `Fake Store API — Portfolio`.
3. Для проверки авторизации заполнить переменные `username` и `password` данными тестового пользователя Fake Store API.
4. Запустить отдельные запросы или коллекцию целиком.

Значения логина, пароля и токена в опубликованном окружении оставлены пустыми.
