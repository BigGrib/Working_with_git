# Инструкция по работе с Markdown

# Заголовки в Markdown
Для создания заголовка в языке Markdown необходимо в начале строки-заголовка написать несколько символов "#". Количество символов "#" показывает уровень заголовка. Чем меньше уровень заголовка, тем крупнее текст заголовка.

## Форматирование текста в языке Markdown
Для написания *курсивного текста* необходимо текст обернуть между двумя символами " * ". Для написания **жирного текста** необходимо обернуть тескт между парой символов " ** ". Для написания ***жирного текста*** необходимо текст обернуть между символами " *** ". 

## Списки в языке Markdown
В языке Markdown существуют списки :
+ нумерованные
+ ненумерованные 

Для создания нумерованного ссписка, необходимо перед каждым пунктом списка в начале строки писать его номер и точку.
Для создания ненумерованного списка необходимо в начале строки перед пунктом писать любой из символов : *, +, -

## Использование цитаты в Markdown 
Для использования цитаты
>Цитата.

Необходимо перед цитатой поставить знак >. Этого достаточно чтобы все думали что 

> Стэйтем сказал что-то умное.



## Использование разделительной черты между строками

Для того, чтобы разделить строки полосой
***
Необходимо на пустой строке между нужными строками поставить (***)
***
***
и тогда черт будет столько сколько строк с ( *** ).

## Использование гиперссылок
[В сибирь]: http://example.com/ 
Гиперссылки разделяются на:
***
1. *Гиперссылка, с немедленным указанием адреса (внутритекстовая)* http://example.com/;
***
2. *Гиперссылка, подобная сноске.* [В сибирь].

Создается по формуле   "["пример"]"(http://example.com/ )"
В квадратных скобках указывается слово с гиперссылко, а в круглых скобках указывается адрес перехода.

## Вставка изображений
Для вставки изображения используется данный способ

![Картинка][image1]

[image1]: https://i.pinimg.com/originals/db/b0/8a/dbb08a069d1f24c4b61da740198a59cc.jpg "Котик"

 Смысл и исполнение такое же как и у гиперссылок, но перед квадратной скобкой ставится " ! ". И в id указывается путь до картинки либо URL. В кавычках указывается текст который мы видим при наведении на картинку.

