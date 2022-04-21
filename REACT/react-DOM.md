# REACT-DOM

# Structure
- Корневой узел
# Корневой узел
- Это узел, содержимым которого управляет ReactDOM.
- В приложении, написанном на React "с нуля", best practice - это один корневой узел.  
Располагается, как правило, следующим образом:

  ```
  <body>
    <div id="root"></div>
  </body>
  ```
- Если __React__ внедряется в существующий проект, то корневых элементов может быть множество.

# UI update
- React DOM обновляет DOM, чтобы он соответствовал переданным React-элементам.
- Обновляет только измененную часть кода  
__React__ сравнивает новую и предыдущую версии DOM-дерева и вносит минимально необходимые изменения, без обновления всего дерева.
- Способы обновления UI:
  - Создание нового элемента и рендеринг в соответствующий узел.  
  Плохой метод. Best-practice - это вызывать ReactDOM.render() один раз, а обновления производить через метод 2.
  - Через компонент с состоянием (_будет изучено позже)_