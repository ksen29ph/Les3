# Туториал по языку разметки MarkDown

## Как добавить заголовки

Заголовки отмечаются диезом `#` в начале строки, от
одного до шести. Например:
# Заголовок первого уровня #
## Заголовок h2
### Заголовок h3
#### Заголовок h4
##### Заголовок h5
###### Заголовок h6
В декоративных целях заголовки можно «закрывать» с
обратной стороны.

## Как добавить исходный код

Чтобы добавить исходный код, необходимо использовать конструкцию следующего вида:
```html
<table><tr><td
style="color:#ff783">Текст</td></tr></table>
```
Пример рабочего кода без кавычек:
<table><tr><td
style="color:#FFD700">Текст</td></tr></table>

## Как добавить таблицы

**В чистом Маркдауне нет синтаксиса для таблиц, а в GFM есть.**

First Header | Second Header
------------- | -------------
Content Cell | Content Cell
Content Cell | Content Cell


**Для красоты можно и по бокам линии нарисовать:**
| First Header | Second Header |
| ------------- | ------------- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |


**Можно управлять выравниванием столбцов при помощи
двоеточия.**
| Left-Aligned | Center Aligned | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is | some wordy text | **$1600** |
| col 2 is | centered | $12 |
| zebra stripes | are neat | ~~$1~~ |


## Как добавить изображения

**Чтобы добавить изображения в разметку MarkDown, используйте следующую конструкцию:**
```
![альтернативный текст](ссылка на изображение)
```
Пример:
![альтернативный текст](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ea/Carina_Nebula.jpg/
240px-Carina_Nebula.jpg)


Чтобы добавить картинку-ссылку, необходимо модифицировать блок-схему выше следующим образом:
```
[![альтернативный текст](ссылка на изображение)](ссылка на изображение или страницу, на которую перейдем, если кликнем по первому изображению)
```

Пример:

[![Прикол](https://dbmast.ru/wp-content/uploads/2014/03/button-css-3d.png)](https://thumbs.gfycat.com/PastSoggyDragon-size_restricted.gif)

**Как добавить ссылки**

Markdown поддерживает два стиля оформления ссылок:
Гиперссылка, с немедленным указанием адреса (внутритекстовая);
Гиперссылка, подобная сноске.
Подразумевается, что помимо URL-адреса существует еще текст ссылки. Он заключается в квадратные скобки. Для
создания внутритекстовой гиперссылки необходимо использовать круглые скобки сразу после закрывающей квадратной.
Внутри них необходимо поместить URL-адрес. В них же возможно расположить название, заключенное в кавычки,
которое будет отображаться при наведении, но этот пункт не является обязательным.
[пример](http://example.com/ "Необязательная подсказка")
