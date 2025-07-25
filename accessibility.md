# ♿ Чек-лист по доступности

## Структура и семантика
- [ ] Используются правильные теги: `header`, `nav`, `main`, `footer`.
- [ ] Логика заголовков не нарушена (h1 > h2 > h3...).

## Скринридеры
- [ ] Все важные элементы имеют `aria-label`.
- [ ] Есть `role` для сложных блоков: `dialog`, `alert`, `tooltip`.
- [ ] Ошибки форм читаемы.

## Контрастность и цвет
- [ ] Контрастность текста достаточна.
- [ ] Нет информации, завязанной только на цвет.

## Частые баги
- [ ] Интерактивный элемент доступен клавиатурой.
- [ ] Нет ловушек фокуса при модалках, каруселях.
- [ ] Нет незаметных интерактивных областей (0x0 пикселей, скрытые кнопки).

<!-- ## Навигация и фокус
- [ ] Четкий порядок фокуса по `Tab`.
- [ ] Фокус виден визуально.
- [ ] Фокус не заперт в неожиданных местах. -->
