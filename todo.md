## TODO

### Новые возможности

  - Implement macroses:
    - `{{toc}}`
    - `{date}` автоматически печатать дату генерации слайдов

  - Билд
    - Move publish-html to this repo
    - Научиться печатать и публиковать PDF на TravisCI

  - introduce global links
  - introduce global pictures (may be just use a single folder)

### Автоматические проверки

  - Содержимое
    - Соблюдается единый формат содержания
      (содержание+toc, контрольные вопросы, м.б. ключевые идеи)
    - Проверять, что контрольные вопросы в слайдах и сводном документе совпадают
    - Снести все ссылки в конец Markdown-файлов

  - Markdown Checks
    - Каким-то образом валидировать Markdown (<http://habrahabr.ru/post/235611/>)
    - Используются стандартные маркеры списков (- и 1.)
    - Использовать двойное подчеркивание для выделения жирным
    - detect unused links
    - Можно проверять, что картинки имеют стандартную высоту, например 500 пикселов

  - Код
    - В блоках кода должно быть одинаковое выравнивание (4 пробела)
    - По идее можно вырезать все куски кода и проверять их на соответствие
      некоторым общим соглашениям (запускать какие-то тулы)

### Стиль

  - Change style for quotes
  - Add line numbers to code, then syntax highlighting
  - Заголовки разных уровней должны визуально отличаться друг от друга

### Остальное

  - Реализовать поддержку
    - plantuml
    - latex formulas
    - Try Graphvis

  - Избавиться от папки `graphics`
  - Изучить диалект pandoc <http://johnmacfarlane.net/pandoc/demo/example9/pandocs-markdown.html>
  - Optional
    - Check <https://code.google.com/p/io-2012-slides/>
    - Можно попробовать интеграцию `reveal.js` с pandoc