# Привет, я Frontent разработчик.👋

## Стек технологий :
<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-plain-wordmark.svg"  title="CSS3" alt="CSS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/typescript/typescript-original.svg" title="TypeScript" alt="TypeScript" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original-wordmark.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/redux/redux-original.svg" title="Redux" alt="Redux " width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original-wordmark.svg" title="Git" alt="Git" width="40" height="40"/>
</div>

## Мои учебные работы :
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

**Интерактивный поиск:**  Динамический поиск навыков с автоматическим обновлением результатов по мере ввода текста.
*   **Redux для управления состоянием:** Централизованное управление состоянием приложения, упрощающее отслеживание и изменение данных.
*   **Redux Saga для асинхронных операций:**  Эффективное управление асинхронными запросами к API с помощью Redux Saga, обеспечивающее плавный пользовательский опыт.
*   **Надежная обработка ошибок:**
    *   Перехват ошибок на уровне Saga с использованием `try...catch`.
    *   Повторные попытки запросов (retry) для повышения устойчивости к временным сбоям.
    *   Отображение информативных сообщений об ошибках в пользовательском интерфейсе.
    *   Использование `AbortController` для отмены устаревших запросов.
*   **Оптимизация производительности:**  Использование debounce для ограничения частоты запросов к API, снижая нагрузку на сервер и улучшая производительность приложения.
*   **Типобезопасность с TypeScript:** Обеспечение типобезопасности и улучшение поддерживаемости кода благодаря использованию TypeScript.

Используемые технологии: React, Redux, Redux Saga, fetch Api, AbortController, TypeScript, Vite.




### :fire: Моя статистика 
 [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=dmiweb&theme=dark)](https://github.com/anuraghazra/github-readme-stats)
 
  [![GitHub Streak](http://github-readme-streak-stats.herokuapp.com?user=dmiweb&theme=dark)](https://git.io/streak-stats)

