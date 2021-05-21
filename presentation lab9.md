# Презентация по лабораторной работе №9

----

# Тема:
## Текстовой редактор vi

----

## Российский Университет Дружбы Народов

### Факультет Физико-Математических и Естественных Наук

*Дисциплина: Операционные системы*

Студент: Бен бадр Ясмин

Группа: НКНбд-01-20

Москва, 2021г.

----
###введение
Текстовый редактор vim, созданный на основе более старого vi. Один из мощнейших текстовых редакторов с полной свободой настройки и автоматизации, возможными благодаря расширениям и надстройкам. По умолчанию входит в состав любого дистрибутива Linux.
Текстовым редактором (text editor) называют программу, которая предназначена для редактирования (составления и изменения) файлов, содержащих только текст, например: письмо, программа на языке C, системный конфигурационный файл.

1. Создала каталог с именем ~/work/os/lab06, Перешела во вновь созданный каталог.
![](https://raw.githubusercontent.com/benbaderyasmine/lab09/main/lab9/Screenshot%202021-05-22%20001149.png)

Вызвала vi и создала файл hello.sh
![](https://raw.githubusercontent.com/benbaderyasmine/lab09/main/lab9/2.png)

![](https://raw.githubusercontent.com/benbaderyasmine/lab09/main/lab9/3.png)

2. Нажав клавишу i, ввела следующий текст:
![](https://raw.githubusercontent.com/benbaderyasmine/lab09/main/lab9/4.png)


1. Нажав клавишу Esc, перешела в командный режим, после завершения ввода текста.

![](https://raw.githubusercontent.com/benbaderyasmine/lab09/main/lab9/4.png)

1. Нажала «:» для перехода в режим последней строки и внизу экрана появилось приглашение в виде двоеточия.

![](https://raw.githubusercontent.com/benbaderyasmine/lab09/main/lab9/5.png)

7. Нажала w (записать) и q (выйти), а затем нажала клавишу Enter для сохранения текста и завершения работы.
![](https://raw.githubusercontent.com/benbaderyasmine/lab09/main/lab9/6.png)

8. Сделала файл исполняемым. 

![](https://raw.githubusercontent.com/benbaderyasmine/lab09/main/lab9/7.png)
#### Задание 2. Редактирование существующего файла.

1. Вызвала vi на редактирование файла.

![](https://raw.githubusercontent.com/benbaderyasmine/lab09/main/lab9/8.png)
 Установила курсор в конец слова HELL второй строки. Перешела в режим вставки и заменила на HELLO. Нажала Esc для возврата в командный режим.

![](https://raw.githubusercontent.com/benbaderyasmine/lab09/main/lab9/10.png)
4. Установила курсор на четвертую строку и стёр слово LOCAL.
 Перешела в режим вставки и набрал следующий текст: local, нажала Esc для возврата в командный режим.

![](https://raw.githubusercontent.com/benbaderyasmine/lab09/main/lab9/11.png)

6. Установила курсор на последней строке файла. Вставила после неё строку, содержащую следующий текст: echo $HELLO.

![](https://raw.githubusercontent.com/benbaderyasmine/lab09/main/lab9/11.png)

7. Нажала Esc для перехода в командный режим.

8. Удалила последнюю строку.

![](https://raw.githubusercontent.com/benbaderyasmine/lab09/main/lab9/12.png)

9. Ввела команду отмены изменений u для отмены последней команды.
![](https://raw.githubusercontent.com/benbaderyasmine/lab09/main/lab9/11.png)

10. Ввела символ «:» для перехода в режим последней строки. Записала произведённые изменения и вышел из vi. 

![](https://raw.githubusercontent.com/benbaderyasmine/lab09/main/lab9/13.png)

----

### Вывод

Познакомилася с операционной системой Linux, получила практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах.

----

