# COMPONENT

## About
- Независимая часть интерфейса представляющая фрагмент кода, содержащая логику и разметку, ..и возвращающая react-элемент.
<<<<<<< HEAD
- Компонент - это основа повторного использования кода.
## Features
- Взаимодействие с пользователем  
Пример: нажатие на кнопку

## HIT
- Компонент может иметь свойства (props) >>>  
Он преобразует пропсы в UI.
- Компонент может иметь состояние (state) >>>
- Компонент принимает пропс и возвращает react-элемент
- Компонент имеет жизненный цикл:
  - Монтирование >>>
  - Обновление >>>
  - Размонтирование >>>
  - Обработка ошибок >>>
=======

## HIT
- Компонент может иметь свойства (props) >>>
- Компонент может иметь состояние (state) >>>
- Компонент принимает пропс и возвращает react-элемент
>>>>>>> 79ff31d41cc22f0141a789840a70d5ed830e0103

## Types
- функциональный (представляет собой функцию)
- классовый (представляет собой класс)

## Characteristics
- __Композиция__  
Компоненты могут встраиваться друг в друга.  
Для этого в возвращаемом компонентом дереве необходимо указать ок-элемент. Пример:

  ```
  return (
    <div>
      <ComponentName/>
    </div>
  )
  ```
- __Переиспользование__  
Компонент можно переиспользовать неограниченное количество раз:

  ```
  <div>
    <ComponentName/>
    <ComponentName/>
    <ComponentName/>
  </div>
  ```
- __Независимость__  
<<<<<<< HEAD
Один компомнент слабо (либо никак) связан с другим компонентом.
=======
Один компомнент слабо (либо никак) связан с другим компонентом.

## Suntax >> Creation Rules
- __Невысокая вложенность__  
- __Невысокая сложность__ 
- __Чистая функция__  
Компонент не должен ничего записывать в свои пропсы.

## Technics
- Самообновление >>>

## ToDo
- Заполнить пункт "самообновление"

## Draft
- Классовый компонент вызывается без дополнительного определения объекта созданного класса.
>>>>>>> 79ff31d41cc22f0141a789840a70d5ed830e0103
