# закрепляе пройденный материал
## задание - создать в центре экратна карточку товара(размер экрана не известен)
 -задали карточке фиксированный размер по ширине и высоте + воспользовались свойством overflow: auto; для формирования скрола если контент не поместица внутри карточки...
 -Сама карточка обсолютна спозиционированна 50% от верха и 50% от левого края + выполнено смещение на -50% от ширины и высоты самой карточки transform: translate(-50%, -50%);
 -познакомились с генераторами изображений(см. интелект карту https://goo.su/front ветка изображение)
 -сформировали кнопку из тега а - добавили в кнопку:
  - display: inline-block; 
  - border: 2px solid #ccc;
  - text-transform: uppercase;
  - letter-spacing: 5px; растояние между буквами
  - border-radius: 10px; скругление углдов
  - transition: 0.8s; задержка
  - воспользовались свойством .btnCard:hover(свойства при наведении курсора мышки на блок)
  - ограничили проект одним экраном
html{
    height: 100%;
}

body{
    height: 100%;
