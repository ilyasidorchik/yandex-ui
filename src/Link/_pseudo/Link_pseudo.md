### pseudo

Делает ссылку в псевдоссылкой. Клик по такой ссылке не вызывает перехода на страницу, указанную в свойстве `href`, а вызывает событие, которое указано в свойстве `onClick`.

Псевдоссылки используются для того, чтобы открыть/скрыть какую-то информацию на странице, например показать всплывающую подсказку.

Для оформления псевдоссылок можно использовать тему `pseudo`.

<!-- props:start -->
| Свойство   | Тип                                                | Описание                       |
| ---------- | -------------------------------------------------- | ------------------------------ |
| pseudo?    | `false \| true`                                    | Псевдоссылка                   |
| onKeyDown? | `(event: KeyboardEvent<ContainerElement>) => void` | Обработчик события `onKeyDown` |
<!-- props:end -->
