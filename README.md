# Привет, я Frontent разработчик.👋

## Мой стек технологий :
<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-plain-wordmark.svg"  title="CSS3" alt="CSS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/typescript/typescript-original.svg" title="TypeScript" alt="TypeScript" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original-wordmark.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/redux/redux-original.svg" title="Redux" alt="Redux " width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original-wordmark.svg" title="Git" alt="Git" width="40" height="40"/>
</div>

## Мое резюме: 
https://docs.google.com/document/d/1NKfu8rPE_DfZmzmSlexE5s5wnFdkwCFp8ZBhX85pMhQ/edit?usp=sharing


## Мои учебные работы :
## _«Система бронирования ж/д билетов»_ 
_(дипломный проект по курсу Frontend-разработчик)_

Дипломный проект представляет собой SPA-приложение «Система бронирования ж/д билетов».
(в качестве API используется готовый внешний сервер)

* Верстка по макетам Figma, также использовал PhotoShop для редактирования экспортированных изображений;
* Основные компоненты:
  - Полоса прогресса загрузки данных;
  - Пагинация;
  - Подписка на новости - с валидацией (pattern) и обработкой ошибок;
  - Поиск билетов - автоматическая подгрузка городов при вводе, выпадающий виджет календаря для выбора даты; 
  - Панель фильтров - множественные фильтры поездов (даты, типы вагонов, опции вагонов, цены, время);
  - Последние билеты;
  - Предпросмотр поезда - список карточек поездов с отображением информации о них и tooltips с ценами нижних и верхних мест;
  - Сортировка поездов - время, стоимость, длительность поездки;
  - Выбор количества отображения поездов на странице - 5, 10, 20;
  - Выбор места - тип пассажира, тип вагона, номер вагона, опции вагона, номер места. Схемы вагонов выполнены методом создания SVG конструкции с наложением на изображение вагона (Interactive Seat Map Creation);
  - Данные пассажира - формы с управляемыми полями и валидацией Constraint Validation API;
  - Данные покупателя - форма с управляемыми полями, валидация Constraint Validation API, маска ввода номера телефона;
  - Детали поездки - боковая панель с деталями поездки 
  - Подтверждение заказа - с возможностью изменения поезда, данных о пассажирах, данных покупателя;
  - Модальное окно;
  - Звездный рейтинг - оценка сервиса на странице успешного заказа.
* Постраничная навигация и переходы работают на React Router (Outlet, Navigate, Location).
* Использование Redux Toolkit для централизованного управления состоянием. Разделение хранилища на несколько слайсов.
* Использование Redux Saga для обработки асинхронных операций, побочных эффектов и отслеживанием ошибок с разделением по их видам. Запросы выполняются с выборкой множества query параметров.
* Обработка ошибок: В воркере саги, внутри while(true) происходит попытка получения данных, в случае ошибки происходит повторение запросов к серверу с экспоненциальной задержкой и после нескольких безуспешных попыток выводится модальное окно с ошибкой и предложением повторить попытку. Предусмотрена отмена устаревших запросов, а также при размонтировании компонента.
* TypeScript для обеспечения типобезопасности и лучшей поддерживаемости кода.

Технологии: React, React Router, Redux Toolkit, Redux Saga, TypeScript, fetch API, Vite, БЭМ.

Репозиторий: https://github.com/dmiweb/train-booking-app

GitHub Page: https://dmiweb.github.io/train-booking-app

## _Интернет-магазин обуви (дипломный проект по React JS)_
Дипломный проект представляет собой интернет-магазин обуви: (серверная часть выложена на бесплатный сервис, деплой может занять некоторое время)

* SPA-приложение со всеми основными функциями которыми можно пользоваться:
  - Главная страница: навигационное меню, виджет дублер поиска, виджет корзины, компонент хиты продаж, компонент каталог; 
  - Каталог товаров: основной поиск, меню категорий товаров, каталог, карточки товаров;
  - Информационная страница;
  - Страница товара: выбор размера, выбор количества;
  - Корзина: возможность удаления товара;
  - страница 404.
* Постраничная навигация осуществляется с помощью React Router.
* Использование Redux Toolkit для централизованного управления состоянием.
* Использование Redux Saga для обработки асинхронных операций и побочных эффектов.
* Обработка ошибок: В воркере саги, внутри while(true) происходит попытка получения данных, в случае ошибки происходит повторение запросов к серверу с экспоненциальной задержкой и после нескольких безуспешных попыток выводится сообщение с ошибкой. Предусмотрена отмена устаревших запросов, а также при размонтировании компонента.
* TypeScript для обеспечения типобезопасности и лучшей поддерживаемости кода.

Технологии: React, React Router, Redux Toolkit, Redux Saga, Bootstrap 5, TypeScript, fetch API, Vite.

Репозиторий: https://github.com/dmiweb/shoe-shop

GitHub Page: https://dmiweb.github.io/shoe-shop

Backend размещен на Render, поэтому первый ответ от сервера может занимать до 1 минуты.

## _Лента новостей_
Этот проект представляет собой React-приложение для агрегации и отображения новостной ленты. Приложение получает данные с удаленного API и отображает их в удобном для пользователя формате. Ключевые особенности включают:

* Динамическая подгрузка новостей по кнопке.
* Поддержка различных типов новостного контента (статьи, видео, посты).
* Использование Redux для централизованного управления состоянием.
* Использование Redux Saga для обработки асинхронных операций и побочных эффектов.
* Обработка ошибок: В воркере саги, внутри while(true) происходит попытка получения данных, в случае ошибки происходит yield delay(3000), и делается еще одна попытка.
* TypeScript для обеспечения типобезопасности и лучшей поддерживаемости кода.

Технологии: React, Redux, Redux Saga, TypeScript, fetch API, Vite.

Репозиторий: https://github.com/dmiweb/news-feed-redux-saga

GitHub Page: https://dmiweb.github.io/news-feed-redux-saga

Backend размещен на Render, поэтому первый ответ от сервера может занимать до 1 минуты.

## _Живой поиск_

Это React-приложение для поиска навыков (skills), использующее Redux для управления состоянием, Redux Saga для обработки асинхронных запросов к API и TypeScript для обеспечения типобезопасности. Приложение позволяет пользователю вводить поисковой запрос, отправляет этот запрос на сервер, получает результаты и отображает их. Также предусмотрена обработка ошибок, отображение состояния загрузки и debounce для оптимизации запросов.

Ключевые особенности:
*   **Интерактивный поиск:**  Динамический поиск навыков с автоматическим обновлением результатов по мере ввода текста.
*   **Redux для управления состоянием.**
*   **Redux Saga для асинхронных операций.**
*   **Надежная обработка ошибок:**
    *   Перехват ошибок на уровне Saga с использованием `try...catch`.
    *   Повторные попытки запросов (retry) для повышения устойчивости к временным сбоям.
    *   Отображение информативных сообщений об ошибках в пользовательском интерфейсе.
    *   Использование `AbortController` для отмены устаревших запросов.
*   **Оптимизация производительности:**  Использование debounce для ограничения частоты запросов к API, снижая нагрузку на сервер и улучшая производительность приложения.
*   **Типобезопасность с TypeScript.**

Используемые технологии: React, Redux, Redux Saga, fetch Api, AbortController, TypeScript, Vite.

Репозиторий: https://github.com/dmiweb/search-redux-saga

GitHub Page: https://dmiweb.github.io/search-redux-saga
<br>Примеры запросов: react, redux.

Backend размещен на Render, поэтому первый ответ от сервера может занимать до 1 минуты.

## _Фильмотека_

Приложение Фильмотека — это веб-приложение, демонстрирующее навыки работы с React, Redux Toolkit, и внешними API. Приложение позволяет искать фильмы по названию, добавлять фильмы в избранное, просматривать подробную информацию о фильме и просматривать список избранных фильмов. Для запросов используется стороннее OMDb API.

Приложение состоит из трёх основных страниц:
* Страница поиска с отображением списка фильмов
* Страница избранного
* Страница подробной информации о фильме

Ключевые особенности приложения:
* Поиск фильмов по названию: Быстрый и удобный поиск фильмов с использованием внешнего API.
* Добавление в избранное: Возможность сохранения понравившихся фильмов в список избранного. Список избранного хранится в Redux store.
* Подробная информация о фильме: Отображение подробной информации о выбранном фильме.
* Обработка ошибок: Надежная обработка ошибок на всех этапах работы приложения.
* Использование Redux Toolkit: Применение Redux Toolkit для управления состоянием приложения.
* Компонентный подход: Использование компонентов для модульности и повторного использования кода.
* Навигация: Простая и интуитивно понятная навигация между страницами приложения.
* Загрузка индикатора: Отображение индикатора загрузки при выполнении асинхронных операций.

Используемые технологии:
React, Redux Toolkit, React Router, Fetch API, TypeScript, Vite.

Репозиторий: https://github.com/dmiweb/my-film-library

GitHub Page: https://dmiweb.github.io/my-film-library

### :fire: Моя статистика 
 [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=dmiweb&theme=dark)](https://github.com/anuraghazra/github-readme-stats)
 
  [![GitHub Streak](http://github-readme-streak-stats.herokuapp.com?user=dmiweb&theme=dark)](https://git.io/streak-stats)

