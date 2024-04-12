---
## Front matter
title: "Лабораторная раота №10"
subtitle: "Текстовой редактор vi"
author: "Дашкина Анита"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Познакомиться с операционной системой Linux. Получить практические навыки рабо-
ты с редактором vi, установленным по умолчанию практически во всех дистрибутивах.

# Задание

1. Ознакомиться с теоретическим материалом.
2. Ознакомиться с редактором vi.
3. Выполнить упражнения, используя команды vi.


# Выполнение лабораторной работы

1. Создайте каталог с именем ~/work/os/lab06.

![создание каталога](image/1.png){#fig:001 width=50%}

2. Перейдите во вновь созданный каталог.

![cd](image/2.png){#fig:002 width=50%}

3. Вызовите vi и создайте файл hello.sh

![vi](image/3.png){#fig:003 width=50%}

![hello.sh](image/4.png){#fig:004 width=50%}

4. Нажмите клавишу i и вводите следующий текст.

![ввод текста](image/5.png){#fig:005 width=50%}

5. Нажмите клавишу Esc для перехода в командный режим после завершения ввода
текста.

6. Нажмите : для перехода в режим последней строки и внизу вашего экрана появится
приглашение в виде двоеточия

![режим последней строки](image/6.png){#fig:006 width=50%}

7. Нажмите w (записать) и q (выйти), а затем нажмите клавишу Enter для сохранения
вашего текста и завершения работы.

![wq](image/7.png){#fig:007 width=50%}

8. Сделайте файл исполняемым

![chmod](image/8.png){#fig:008 width=50%}

8.3.2. Задание 2. Редактирование существующего файла

1. Вызовите vi на редактирование файла

2. Установите курсор в конец слова HELL второй строки.

![курсор в конце HELL](image/9.png){#fig:009 width=50%}

3. Перейдите в режим вставки и замените на HELLO. Нажмите Esc для возврата в команд-
ный режим.

![заменим на HELLO](image/10.png){#fig:010 width=50%}

4. Установите курсор на четвертую строку и сотрите слово LOCAL.

![курсор на четвертой строке](image/11.png){#fig:011 width=50%}
![удаление LOCAL](image/12.png){#fig:012 width=50%}

5. Перейдите в режим вставки и наберите следующий текст: local, нажмите Esc для
возврата в командный режим.

![local](image/13.png){#fig:013 width=50%}

6. Установите курсор на последней строке файла. Вставьте после неё строку, содержащую
следующий текст: echo $HELLO.

![курсор на последней строке файла](image/14.png){#fig:014 width=50%}
![вставка текста](image/15.png){#fig:015 width=50%}

7. Нажмите Esc для перехода в командный режим.

![переход в командный режим](image/16.png){#fig:016 width=50%}

8. Удалите последнюю строку.

![удвление строки](image/17.png){#fig:017 width=50%}

9. Введите команду отмены изменений u для отмены последней команды.

![отмена команды](image/18.png){#fig:018 width=50%}

10. Введите символ : для перехода в режим последней строки. Запишите произведённые
изменения и выйдите из vi.




# Выводы

Мы познакомились с операционной системой Linux. Получили практические навыки рабо-
ты с редактором vi, установленным по умолчанию практически во всех дистрибутивах.

# Список литературы{.unnumbered}

