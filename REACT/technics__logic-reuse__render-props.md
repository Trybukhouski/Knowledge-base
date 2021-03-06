# RENDER-PROPS

## About
- Рендер-проп - это проп компонента, который принимает функцию, возвращающую react-элемент, который можно затем использовать в компоненте для динамического рендеринга. 
[При этом этот элемент заменяет реализацию компонентом собственного рендера]?
- Техника рендер-пропов применяется в следующих библиотеках:
  - React Router
  - Downshift
  - Formik

## Scope of use
- Разделение (вместо копирования) одной функциональности (логики, состояния и поведения) между компонентами, заинтересованных в ней.

## Creation >> Global rules
- Название рендер-пропа может быть произвольным (не обязательно `render`). Главное, чтобы он содержал функцию рендеринга.

## Creation >> Algorytm
1. Выделяем переиспользуемую логику в отдельный компонент.
1. В рендер-методе этого компонента ссылаемся на рендер-проп, который будет отвечать за динамический рендеринг этой части рендера.

    ```
    this.props.render(args)
    ``` 
1. Установленному компоненту присваиваем атрибут `render` со значением-функцией, уписывающей UI для рендеринга.

    ```
    render={
      (args) => code-for-rendering
    }
    ```

## Practice examples
- Динамический рендеринг html-элемента >> _Render-props - Greeting_
- Пример >> (_RenderProps_)