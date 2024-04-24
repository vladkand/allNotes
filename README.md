# allNotes
Notes

* - ## inline-flex применяют для кнопок, иконок декор элементов(ЧТО-Б не занимали весь ряд)  и др.

*  -  ## BUTTON ==>>
   -  button {
           -outline: none;
           -border: none;
           -font-size: 100%;
           -margin: 0;
           -line-height: normal;
            }

* - ## При position: absolut;
  -  ==> элемент становится display: block;
      Ширина элемента с position: absolute устанавливается по содержимому. Детали алгоритма вычисления ширины описаны в стандарте.
      Элемент получает display: block, который перекрывает почти все возможные display
* - ## Ссылки:
  - для ссылок Используя target, вы должны добавлять rel="noopener noreferrer", чтобы избежать эксплуатацию API window.opener.
* - ## UNSET ==>> отменяет(сбрасывает) значение стилей:
  - .myclass{
      - margn-bottom: 20px;
        - @media screen and (min-width: 1200px) {
         - margin-bottom: unset;
          }
       }
    
