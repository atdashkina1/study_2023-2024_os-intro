---
## Front matter
title: "Отчет о выполнении индивидуального проекта.Этап 1"
subtitle: 
author: "Дашкина Анита Тагировна"


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

Размещение на Github pages заготовки для персонального сайта.


# Задание

  Установить необходимое программное обеспечение.
    Скачать шаблон темы сайта.
    Разместить его на хостинге git.
    Установить параметр для URLs сайта.
    Разместить заготовку сайта на Github pages.


# Теоретическое введение


# Выполнение индивидуального проекта

Скачиваем hugo exstending.Создаем папку bin и вставляем файл hugo.

![hugo](image/1.png){#fig:001 width=70%}

Создаем репозиторий blog 

![репозиторий blog](image/2.png){#fig:002 width=70%}

Клонируем репозиторий blog 

![Клонируем репозиторий blog](image/3.png){#fig:003 width=70%}

Перейдем в blog и выполним команду ~/bin/hugo server.Проверяем папку 

![выполняем команду](image/4.png){#fig:004 width=70%}

Удаляем папку public

![Удаляем папку public](image/5.png){#fig:005 width=70%}

![Проверяем](image/6.png){#fig:006 width=70%}

Выполним команду ~/bin/hugo server переходим по ссылке localhost и уберем шапку сайта.Перейдем для этого в папку content и отредактируем файл index.md

![выполняем команду](image/7.png){#fig:007 width=70%}

Создаем новый репозиторий 

![Создаем новый репозиторий](image/8.png){#fig:008 width=70%}

Клонируем репозиторий mkarapaaa.github.io

![Клонируем репозиторий](image/9.png){#fig:009 width=70%}

Подключим ветку main

![Подключим ветку main](image/10.png){#fig:010 width=70%}

Создадим пустой файл REDME.md 

![Создадим пустой файл](image/11.png){#fig:011 width=70%}

Перейдем в файл .gitignore и отредактируем

![Редактируем файл .gitignore](image/12.png){#fig:012 width=70%}

Введем команду submodule

![выполняем команду](image/13.png){#fig:013 width=70%}

Наполним папку public, используя команду ~/bin/hugo 

![Наполняем папку public](image/14.png){#fig:014 width=70%}

Перейдем в папку public,проверим,отправим все на github.

![Проверяем и отправляем на github](image/15.png){#fig:015 width=70%}

Проверим наш сайт

![Проверим сайт](image/16.png){#fig:016 width=70%}


# Выводы

Размещение на Github pages заготовки для персонального сайта.


