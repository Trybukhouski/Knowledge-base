# RENDERING

## Варианты обновления UI
- Через ReactDOM.render()

  ```
  ReactDOM.render(React-elem, DOM-elem[, callback])
  ```
  - `ReactDOM` - это...
  - `React-elem` - React-элемент, который мы рендерим в DOM-узел.
  - `DOM-elem` - DOM-узел, в который мы рендерим React-элемент.
  - `callback` - коллбэк-функция, которая вызовется после того, когда компонентся отрендерится или обновится.
  - `render()` - метод для рендеринга React-элемента в DOM-элемент.  
  Возвращает ссылку на компонент. Если у компонента нет состояния - `null`.

- Самообновление компонента  
?Компонент инкапсулируется, чем обеспечивается его многократное использование.?  
Происходит через state.