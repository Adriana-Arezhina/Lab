# Отчёт о выполнении лабораторной работы №9

***Российский Университет Дружбы Народов***  
***Факультет Физико-Математических и Естественных Наук***

***Дисциплина:*** *Операционные системы*

***Работу выполняла:*** *Арежина Адриана*

***№ ст. билета:*** *1032201674*

***Группа:*** *НКНбд-01-20*

***Москва. 2021г.***


## Цель работы

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах.

## Задание 1

1. Создайте каталог с именем ~/work/os/lab06.
2. Перейдите во вновь созданный каталог.
3. Вызовите vi и создайте файл hello.sh
4. Нажмите на клавишу *i* и вводите следующий текст:
>#!/bin/bash
>
>HELL=Hello
>
>function hello {
>
>   LOCAL HELLO=World
>
>   echo $HELLO
> }
>
>echo $HELLO
>
>hello
5. Нажмите клавишу *Esc* для перехода в командный режим после завершения ввода текста.
6. Нажмите *:* для перехода в режим последней строки и внизу вашего экрана появится приглашение в виде двоеточия.
7. Нажмите *w* (записать) и *q* (выйти), а затем нажмите клавишу *Enter* для сохранения вашего текста и завершения работы.
8. Сделайте файл исполняемым.

## Задание 2

1. Вызовите vi на редактирование файла *hello.sh*.
2. Установите курсор в конец слова *HELL* второй строки.
3. Перейдите в режим вставки и замените на *HELLO*. Нажмите *Esc* для возврата в командный режим.
4. Установите курсор на четвёртую строку и сотрите слово *LOCAL*.
5. Перейдите в режим вставки и наберите следующий текст: *local*, нажмите *Esc* для возврата в командный режим.
6. Установите курсор на последней строке файла. Вставьте после неё строку, содержащую следующий текст: *echo $HELLO*.
7. Нажмите *Ecs* для перехода в командный режим.
8. Удалите последнюю строку.
9. Введите команду отмены изменений *u* для отмены последней команды.
10. Введите символ *:* для перехода в режим последней строки. Запишите произведённые изменения и выйдите из vi.

## Выполнение работы

### Задание 1

1. Создала каталог с именем *~/work/os/lab06*.
2. Перешла во вновь созданный каталог. (см. рисунок ниже [Новый каталог](https://github.com/Adriana-Arezhina/Lab/blob/main/Lab09/pict/1.1.JPG))
![Новый каталог](https://github.com/Adriana-Arezhina/Lab/blob/main/Lab09/pict/1.1.JPG)

3. Вызвала vi и создала файл *hello.sh* с помощью команды *vi hello.sh*. (см. рисунок ниже [вызов](https://github.com/Adriana-Arezhina/Lab/blob/main/Lab09/pict/1.1.5.JPG))
![вызов](https://github.com/Adriana-Arezhina/Lab/blob/main/Lab09/pict/1.1.5.JPG)
4. Нажала клавишу *i* и ввела текст.
5. Нажала клавишу *Esc* для перехода в командный режим после завершения ввода текста. (см. рисунок ниже [текст](https://github.com/Adriana-Arezhina/Lab/blob/main/Lab09/pict/1.3.JPG))
![текст](https://github.com/Adriana-Arezhina/Lab/blob/main/Lab09/pict/1.3.JPG)
6. Нажала *:* для перехода в режим последней строки.
7. Нажала *w* (записать) и *q* (выйти), а затем нажала клавишу *Esc* для сохранения текста и завершения работы.
8. Сделала файл исполняемым с помощью команды *chmod +x hello.sh*. (см. рисунок ниже [исполнение](https://github.com/Adriana-Arezhina/Lab/blob/main/Lab09/pict/1.4.JPG))
![исполнение](https://github.com/Adriana-Arezhina/Lab/blob/main/Lab09/pict/1.4.JPG)

### Задание 2

1. Вызвала vi на редактирование файла с помощью команды *vi hello.sh*.
2. Установила курсор в конце слова *HELL* второй строки.
3. Перешла в режим вставки и заменила на *HELLO*. Нажала *Esc* для возврата в командный режим. (см. рисунок ниже [HELLO](https://github.com/Adriana-Arezhina/Lab/blob/main/Lab09/pict/2.1.JPG))
![HELLO](https://github.com/Adriana-Arezhina/Lab/blob/main/Lab09/pict/2.1.JPG)
4. Установила курсор на четвёртую строку и стёрла слово *LOCAL*.
5. Перешла в режим вставки и набрала следующий текст: *local*, нажала *Esc* для возврата в командный режим. (см. рисунок ниже [local](https://github.com/Adriana-Arezhina/Lab/blob/main/Lab09/pict/2.2.JPG))
![local](https://github.com/Adriana-Arezhina/Lab/blob/main/Lab09/pict/2.2.JPG)
6. Установила курсор на последней строке файла. Вставила после неё строку, содержащую следующий текст: *echo $HELLO*. (см. рисунок ниже [строка](https://github.com/Adriana-Arezhina/Lab/blob/main/Lab09/pict/2.3.JPG))
![строка](https://github.com/Adriana-Arezhina/Lab/blob/main/Lab09/pict/2.3.JPG)
7. Нажала *Esc* для перехода в командный режим.
8. Удалила последнюю строку. (см. рисунок ниже [удаление](https://github.com/Adriana-Arezhina/Lab/blob/main/Lab09/pict/2.4.JPG))
![удаление](https://github.com/Adriana-Arezhina/Lab/blob/main/Lab09/pict/2.4.JPG)
9. Ввела команду отмены изменений *u* для отмены последней команды. (см. рисунок ниже [u](https://github.com/Adriana-Arezhina/Lab/blob/main/Lab09/pict/2.3.JPG))
![u](https://github.com/Adriana-Arezhina/Lab/blob/main/Lab09/pict/2.3.JPG)
10. Ввела символ *:* для перехода в режим последней строки. Записала произведённые изменения и вышла из vi.

## Контрольные вопросы

1. Командный режим предназначен для ввода команд редактирования и навигации по редактируемому файлу;
режим вставки предназначен для ввода содержания редактируемого файла;
режим последней (командной) строки используется для записи изменений в файл и выхода из редактора.

2. Перейти в режим последней строки: находясь в
командном режиме, нажать двоеточие и набрать символ *q*.

3. Команды позиционирования: 
- 0 (ноль) — переход в начало строки;
- $ — переход в конец строки;
- G — переход в конец файла; 
- n G — переход на строку с номером n.

4. Строка символов, которая может включать в себя буквы, цифры и символы подчёркивания.

5. 0 (ноль) - перейти в начало строки;
$ - перейти в конец строки;

6. Вставка текста:
- а — вставить текст после курсора;
- А — вставить текст в конец строки;
- i — вставить текст перед курсором;
- n i — вставить текст n раз;
- I — вставить текст в начало строки.

Вставка строки:
- о — вставить строку под курсором;
- О — вставить строку над курсором.

Удаление текста:
- x — удалить один символ в буфер;
- d w — удалить одно слово в буфер;
- d $ — удалить в буфер текст от курсора до конца строки;
- d 0 — удалить в буфер текст от начала строки до позиции курсора;
- d d — удалить в буфер одну строку;
- n d d — удалить в буфер n строк.

Отмена и повтор произведённых изменений:
- u — отменить последнее изменение;
- . — повторить последнее изменение.

Копирование текста в буфер:
- Y — скопировать строку в буфер;
- n Y — скопировать n строк в буфер;
- y w — скопировать слово в буфер.

Вставка текста из буфера:
- p — вставить текст из буфера после курсора;
- P — вставить текст из буфера перед курсором.

Замена текста:
- c w — заменить слово;
- n c w — заменить n слов;
- c $ — заменить текст от курсора до конца строки;
- r — заменить слово;
- R — заменить текст.

Поиск текста:
- / текст — произвести поиск вперёд по тексту указанной строки символов;
- ? текст — произвести поиск назад по тексту указанной строки символов.

Команды редактирования в режиме командной строки.

Копирование и перемещение текста:
- : n,m d — удалить строки с n по m;
- : i,j m k — переместить строки с i по j, начиная со строки k;
- : i,j t k — копировать строки с i по j в строку k;
- : i,j w имя-файла — записать строки с i по j в файл с именем имя-файла.

Запись в файл и выход из редактора:
- : w — записать изменённый текст в файл, не выходя из vi;
- : w имя-файла — записать изменённый текст в новый файл с именем имяфайла;
- : w ! имя-файла — записать изменённый текст в файл с именем имяфайла;
- : w q — записать изменения в файл и выйти из vi;
- : q — выйти из редактора vi;
- : q ! — выйти из редактора без записи;
- : e ! — вернуться в командный режим, отменив все изменения, произведённые со времени последней записи.

7. c$ - заменить текст от курсора до конца строки.

8. u- отменить последнее изменение.

9. Kопирование и перемещение текста:
- :n,m d-уничтожить строки с n по m
- : i,j m k- переместить строки с i по j , начиная со строки k
- : i,j t k- копировать строки с i по j на строку k
- : i,j w <имя_файла>- записать строки с i по j в файл с именем <имя_файла>

Запись в файл и выход из редактора:
- :w- записать измененный текст в файл на диске, не выходя из Vi;
- :w <newfile>- записать измененный текст в новый файл с именем <newfile>;
- :w! <имя_файла>- записать измененный текст в файл с именем<имя_файла> ; -
- :wq- записать изменения в файл и выйти из Vi;
- :q- выйти из редактора Vi;
- :q!- выйти из редактора без записи;
- :e!- вернуться в командный режим, отменив все изменения,произведенные со времени последней записи.

10. Командой $.

11. : set all - вывести полный список опций.

12. Нажатие клавиши *Esc* всегда переводит vi в командный. Если Вы нажмете клавишу *Esc*, находясь в командном режиме, машина напомнит вам об этом, подав звуковой сигнал.

13. Командный –> вставки– > последняя строка (командная строка).

## Вывод

Я познакомилась с операционной системой Linux, получила практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах.