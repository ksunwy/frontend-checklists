# 📊 Чек-лист для таблиц

## Визуальные ошибки
- [ ] Заголовки таблицы читаемы, не обрезаются.
- [ ] Ровные отступы между ячейками.
- [ ] Строки не съезжают при скролле.
- [ ] Четкие границы ячеек (если предусмотрены).
- [ ] Корректное отображение пустых данных.

## Функциональные ошибки
- [ ] Сортировка данных работает корректно.
- [ ] Фильтрация не приводит к багам отображения.
- [ ] Пагинация корректно считает страницы и элементы.
- [ ] У пустых таблиц отображается заглушка.

## UX ошибки
- [ ] Строки кликабельны, если по задумке это нужно.
- [ ] Ховеры по строкам работают одинаково.
- [ ] Переход между страницами не теряет выбранные фильтры.
- [ ] Для возможно большого контента добавлено ограничение по высоте.

## Accessibility (a11y)
- [ ] Используются `table`, `thead`, `tbody`, `th`.
- [ ] Заголовки связаны с ячейками (scope, aria).
- [ ] Таблица читаема для скринридеров.
- [ ] Отсутствуют некорретные теги для таблицы.

## Частые баги
- [ ] Скроллы не перекрывают контент.
- [ ] Фиксированные колонки или заголовки не ломают вёрстку.
- [ ] Форматирование чисел, дат, валют соблюдено.
