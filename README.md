# Посты

Создайте страницу, которая загружает посты из [JSONPlaceholder](https://jsonplaceholder.typicode.com/) и выводит их на страницу в виде карточек.

## API

Основной эндпоинт: `https://cataas.com/api/cats`, либо любой другой который сможете найти

Откройте эту ссылку в браузере и изучите структуру JSON-ответа. Изучите что содержится внутри JSON:

## Задание

В репозитории есть файл `index.html` с готовой разметкой. Ваша задача - написать `script.js`, и добавить стили к карточке, чтобы выглядело аккуратно.

### Вывести все посты

1. При загрузке страницы сделать `fetch` к `https://cataas.com/api/cats`
2. Ответ - это массив из 10 объектов (котов)
3. С помощью цикла `for` пройдитесь по массиву и для каждого кота создайте карточку на странице

### Доп. задание

1. Выведите только первые 5 котов, а не все 10

## Полезные ссылки

- [JSONPlaceholder документация](https://jsonplaceholder.typicode.com/)
- [MDN: fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch)
- [MDN: Работа с JSON](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON)
- [MDN: String.prototype.slice()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/slice)
