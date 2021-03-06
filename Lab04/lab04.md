# Отчёт о выполнении лабораторной работы №4

***Российский Университет Дружбы Народов***  
***Факультет Физико-Математических и Естественных Наук***

***Дисциплина:*** *Операционные системы*

***Работу выполняла:*** *Арежина Адриана*

***№ ст. билета:*** *1032201674*

***Группа:*** *НКНбд-01-20*

***Москва. 2021г.***

## Цель работы

Познакомиться с операционной системой Linux, получить практические навыки рабо-
ты с консолью и некоторыми графическими менеджерами рабочих столов операционной
системы.

## Задание

1. Ознакомиться с теоретическим материалом.
2. Загрузить компьютер.
3. Перейти на текстовую консоль. Сколько текстовых консолей доступно на вашем ком-
   пьютере?
4. Перемещаться между текстовыми консолями. Какие комбинации клавиш необходимо
   при этом нажимать?
5. Зарегистрироваться в текстовой консоли операционной системы. Какой логин вы при
   этом использовали? Какие символы отображаются при вводе пароля?
6. Завершить консольный сеанс. Какую команду или комбинацию клавиш необходимо
   для этого использовать?
7. Переключиться на графический интерфейс. Какую комбинацию клавиш для этого
   необходимо нажать?
8. Ознакомиться с менеджером рабочих столов. Как называется менеджер, запускаемый
   по умолчанию?
9. Поочерёдно зарегистрироваться в разных графических менеджерах рабочих столов
   (GNOME, KDE, XFCE) и оконных менеджерах (Openbox). Продемонстрировать разницу
   между ними, сделав снимки экрана (скриншоты). Какие графические менеджеры
   установлены на вашем компьютере?
10. Изучить список установленных программ. Обратить внимание на предпочтитель-
    ные программы для разных применений. Запустите поочерёдно браузер, текстовой
    редактор, текстовой процессор, эмулятор консоли. Укажите названия программ.

## Выполнение работы

1. Ознакомилась с теоретическим материалом и загрузила компьютер.
2. Перешла на текстовую консоль. Она выглядит как командная строка. На моем компьютере доступно 6 текстовых консолей.
   ![текстовые консоли](https://github.com/Adriana-Arezhina/Lab/blob/main/Lab04/pict/3.JPG)
3. Переместилась между текстовыми консолями, нажимая комбинацию клавиш *ALT+(F1-F6)*.
4. Зарегистрировалась в текстовой консоли операционной системы, используя свой логин и пароль.
5. Завершила консольный сеанс, используя команду *logout* или сочетание клавиш *ctrl + Alt + Fn*.
6. Переключилась на графический интерфейс, используя комбинацию клавиш *Ctrl + alt + F7*.
7. Ознакомилась с менеджером рабочих столов. Менеджер, запускаемый по умолчанию называется GNOME
   ![менеджеры рабочих столов](https://github.com/Adriana-Arezhina/Lab/blob/main/Lab04/pict/8.JPG)
8. Поочерёдно зарегистрировалась в разных графических менеджерах рабочих столов (GNOME, KDE, XFCE) и оконных менеджерах (Openbox). На моем компьютере установлены следующие графические менеджеры:
   ![Gnome](https://github.com/Adriana-Arezhina/Lab/blob/main/Lab04/pict/gnome.JPG)
   ![XFCE](https://github.com/Adriana-Arezhina/Lab/blob/main/Lab04/pict/9.JPG)
   ![KDE](https://github.com/Adriana-Arezhina/Lab/blob/main/Lab04/pict/kde.JPG)
9. Изучила список установленных программ. Обратила внимание на предпочтительные программы для разных применений. Запустите поочерёдно браузер, текстовый редактор, текстовой процессор, эмулятор консоли.

## Контрольные вопросы

1. Компьютерный терминал—устройство ввода–вывода,основные функции которого заключаются в вводе и отображении данных. Текстовый терминал (терминал,текстовая консоль)—интерфейс ком-пьютера для последовательной передачи данных. По моему мнению графический интерфейс понятнее.

2. Входное имя - название учётной записи пользователя, которое нужно вводить при регистрации пользователя в системе.

3. Пароли пользователей хранятся в зашифрованном виде в файле /etc/shadow. Файл /etc/shadow доступен только для чтения и может читаться исключительно пользователем root. В разделе, посвященном правам доступа к файлам, мы поговорим о том, как пользователям удается изменять свои пароли.

4. Операционная система Linux в отличие от Windows не имеет общего реестра для хранения настроек системы, все настройки хранятся в конфигурационных файлах. Большинство этих файлов размещено в папке /etc/. Настройки большинства системных и сторонних программ находятся в этих файлах, это могут быть настройки графического сервера, менеджера входа, системных служб, веб-сервера, системы инициализации.

5. Учётная запись пользователя с UID=0 называется root и присутствует в любой системе типа Linux. Пользователь root имеет права администратора и может выполнять любые действия в системе.

6. Да.

7. Процедура регистрации в системе обязательна для Linux. Каждый пользователь операционный системы имеет определенные ограничения на возможные с его стороны действия: чтение, изменение, запуск файлов, а также на ресурсы: пространство на файловой системе, процессорное время для выполнения текущих задач (процессов).При этом действия одного пользователя не влияют на работу другого.Такая модель разграничения доступа к ресурсам операционной системы получила название многопользовательской.

8. Учётная запись пользователя содержит:

   –входное имя пользователя (Login Name);

   –пароль (Password);

   –внутренний идентификатор пользователя (User ID);

   –идентификатор группы (Group ID);

   –анкетные данные пользователя (General Information);

   –домашний каталог (Home Dir);

   –указатель на программную оболочку (Shell)

9. Внутренний идентификатор пользователя в системе (User ID,UID) Group ID(GID).

10. Анкетные данные пользователя (General Information или GECOS)являются необязательным параметром учётной записи и могут содержать реальное имя пользователя(фамилию,имя),адрес,телефон.

11. Домашний каталог - директория в Unix - подобных операционных системах , содержащая домашние директории пользователей . В домашних директориях хранятся документы и настройки пользователя.

12. /home

13. да

14. Учётные записи пользователей хранятся в файле/etc/passwd,который имеет следующую структуру:login:password:UID:GID:GECOS:home:shell

15. Символ \* в поле password некоторой учётной записи в файле/etc/passwd означает,что пользователь не сможет войти в систему.

16. Виртуальные консоли— реализация концепции многотерминальной работы в рамках одного устройства.

17. getty (сокращение от get teletype) — программа для UNIX-подобных операционных систем, управляющая доступом к физическим и виртуальным терминалам (tty).

18. Сеанс (от фр. séance — заседание, букв. «присест»), сессия — в информационных технологиях — период работы учётной записи пользователя между авторизацией и её завершением. В информационных системах сеанс представляет собой запись факта авторизации пользователя и, в некоторых системах, запись времени автоматического завершения работы.

19. Toolkit (Tk,«набор инструментов»,«инструментарий»)—кроссплатформенная библиотека базовых элементов графического интерфейса, распространяемая с открытыми исходными текстами
    Используются следующие основныетулкиты:

–GTK+ (сокращение от GIMP Toolkit) — кроссплатформенная библиотека элементов интерфейса;

–Qt—кросс-платформенный инструментарий разработки программного обеспечения на языке программирования C++.GTK+ состоит из двух компонентов:

–GTK—содержит набор элементов пользовательского интерфейса (таких,как кнопка,список,поле для ввода текста ит.п.) для различных задач;

–GDK — отвечает за вывод информации на экран, может использовать для этого X Window System, Linux Framebuffer, WinAPI. На основе GTK+ построены рабочие окружения GNOME,LXDE и Xfce. Естественно,эти тулкиты могут использоваться и за пределами «родных» десктопных окружений. Qt используется в среде KDE (Kool Desktop Environment)

## Вывод

Я познакомилась с операционной системой Linux, получила практические навыки работы с консолью и некоторыми графическими менеджерами рабочих столов операционной системы.