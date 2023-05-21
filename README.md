# Тестове завдання ✅

<b>Мета:</b> створити картки твітів та додати інтерактивності при клікові на кнопку.

###

![requirmentsImg](https://github.com/Artemdream/test-tweets-tasks/blob/master/src/images/BGC.png)

###

Загальний вигляд картки у двох станах - Follow та Following

###

# Критерії виконання

- Верстка фіксована в `рх`, семантична та валідна.
- Немає помилок в консолі браузера.
- Робота виконана на нативному `JS` з використанням зборщиків або на `React`.
- Інтерактивність працює відповідно до технічного завдання.
- Код відформатований та без коментарів.
- В репозиторії має бути описаний `README.md`.

###

# Технічне завдання

- Відповідно до [макету](https://www.figma.com/file/zun1oP6NmS2Lmgbcj6e1IG/Test?node-id=0-1&t=fKfPK1hQF3isHhAC-0) потрібно реалізувати картки юзера.
- При клікові на кнопку `Follow` - текст змінюється на `Following`. Також змінюється колір кнопки. А до кількості фоловерів додається і ваш. Тобто, початкова кількість складає `100,500` фоловерів. При клікові на кнопку буде `100,501`.
- При оновлені сторінки має фіксуватись кінцевий результат дій юзера. Тобто, якщо клікнути по кнопці і оновити сторінку - то кнопка все рівно залишається в стані `Following` із відповідним кольором, а кількість фоловерів НЕ зменшується до початкового значення.
- При повторному клікові на кнопку її текст та колір змінюються до початкового стану. Також змінюється і кількість фоловерів. Вона зменшується на 1 `(100,500)`.
  В коді цифра `100,500` має бути прописана одним значенням `(100500)`. В UI - виведено через кому `(100,500)`.

###

Створи свій персональний бекенд для розробки за допомогою UI-сервісу [mockapi.io](https://mockapi.io). Створи ресурс users. Використай конструктор ресурсу та опиши об'єкт юзера, як описано нижче.

###

### Юзер

###

- Створюєте юзера в Mockapi з наступними полями: `id`, `user`, `tweets`, `followers`, `avatar`.

```js
[
  {
    id: "1",
    user: "Elon Mask",
    tweets: 777,
    followers: 10500,
    avatar: "url.jpg",
  },
];
```


# Додаткове завдання

<b>За виконання вам будуть нараховані додаткові бали! Без виконання додаткового завдання ви не зможете отримати максимальний бал.</b>

###

<b>Створи маршрутизацію, використовуючи React Router.</b>

###

У застосунку повинні бути такі маршрути. Якщо користувач зайшов за неіснуючим маршрутом, його необхідно перенаправляти на домашню сторінку. `'/'` – компонент `Home`, домашня сторінка. Стилізація та оформлення на ваш розсуд `'/tweets'` - компонент `tweets`, сторінка із відображенням твітів На сторінці `tweets` має бути кнопка `Back`, яка веде на головну сторінку.

###

### Завдання із зірочкою

###

Додай фільтрацію. Це має бути Dropdown із 3 опціями(оформлення на ваш розсуд): show all, follow, followings show all - показати всі твіти. follow - показати твіти, у яких стан follow. followings - показати твіти, у яких стан following
