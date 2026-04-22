# Посты

Создайте страницу, которая загружает посты из [JSONPlaceholder](https://jsonplaceholder.typicode.com/) и выводит их на страницу в виде карточек.

## API

Основной эндпоинт: `https://jsonplaceholder.typicode.com/posts`, либо любой другой который сможете найти, например `https://cataas.com/api/cats` (рабочий)

Откройте эту ссылку в браузере и изучите структуру JSON-ответа. Изучите что содержится внутри JSON:

Также есть эндпоинт для комментариев к посту: `https://jsonplaceholder.typicode.com/posts/1/comments`

## Задание

В репозитории есть файл `index.html` с готовой разметкой. Ваша задача - написать `script.js`, и добавить стили к карточке, чтобы выглядело аккуратно.

### Вывести все посты

1. При загрузке страницы сделать `fetch` к `https://jsonplaceholder.typicode.com/posts`
2. Ответ - это массив из 100 объектов (постов)
3. С помощью цикла `for` пройдитесь по массиву и для каждого поста создайте карточку на странице
4. В карточке должно быть: номер поста (`id`), заголовок (`title`), текст (`body`)

### Превью текста

1. Показывайте не весь текст поста, а только первые 50 символов с многоточием в конце
   - это можно сделать через `.slice(0, 50) + "..."`
2. Выведите только первые 20 постов, а не все 100

## Полезные ссылки

- [JSONPlaceholder документация](https://jsonplaceholder.typicode.com/)
- [MDN: fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch)
- [MDN: Работа с JSON](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON)
- [MDN: String.prototype.slice()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/slice)
