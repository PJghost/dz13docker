добрый день, сегодня делаем домашку по докеру,
Сперва подготавливаем докер файл, который нам даст нгинкс и пробросит порты

![скрин](/dz13scr1.png)
![скрин](/dz13scr2.png)
Вуаля сервис поднят и наша страница доступна.
Легко заметить что контейнер легковеснее образа, и потребляет меньше ресурсов

На втором этапе поднимаем контейнер с новым именем и пушим его в докер хаб, всё пршошло успешно

![скрин](/dz13scr3.png)
![скрин](/dz13scr4.png)

Поиск показал что ядро то собрать можно, но загрузится с него нет, т.к. контейнер стартует из текущего окружения.
