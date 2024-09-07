---
## Front matter
title: "Отчёт о лабораторной работе"
subtitle: "Лабораторная работа 1"
author: "Андрюшин Никита Сергеевич"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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

Установить Linux Rocky и ознакомиться с его возможностями

# Задание

Установить ОС и выдолнить домешнее задание

# Выполнение лабораторной работы

Для начала назовём нашу виртуалку и выберем установочный диск (рис. [-@fig:001]).

![Выбор диска](image/1.jpg){#fig:001 width=70%}

Выделим память и процессор (рис. [-@fig:002]).

![Выделение памяти и процессора](image/2.jpg){#fig:002 width=70%}

Выделим размер диска. Будет 30 гб (рис. [-@fig:003]).

![Выделение диска](image/3.jpg){#fig:003 width=70%}

Здесь мы выберем русский язык (рис. [-@fig:004]).

![выбор языка](image/4.jpg){#fig:004 width=70%}

Выберем диск, куда установится система (рис. [-@fig:005]).

![Выбор диска](image/5.jpg){#fig:005 width=70%}

Отключим kdump (рис. [-@fig:006]).

![Отключение kdump](image/6.jpg){#fig:006 width=70%}

Настроим сеть. В качестве имени узла выберем nsandryushin.localdomain (рис. [-@fig:007]).

![Настройка сети](image/7.jpg){#fig:007 width=70%}

Настроим рут пользователя, указав пароль для него и разрешив ему ssh (рис. [-@fig:008]).

![Название рисунка](image/8.jpg){#fig:008 width=70%}

Настроим своего пользователя согласно соглашению об именовании (рис. [-@fig:009]).

![Настройка пользователя](image/9.jpg){#fig:009 width=70%}

Ждём завершения установки. По завершении видем следующее и перезагружаемся (рис. [-@fig:010]).

![Экран окончания установки](image/10.jpg){#fig:010 width=70%}

После перезугрузки установим дополнения гостевой ОС (рис. [-@fig:011]).

![Установка дополнений](image/11.jpg){#fig:011 width=70%}

Вот как выглядит завершение установки (рис. [-@fig:012]).

![Завершение установки](image/12.jpg){#fig:012 width=70%}

Теперь выполним домашнее задание. Найдём версию ядра (рис. [-@fig:013]).

![Версия ядра](image/13.jpg){#fig:013 width=70%}

И частоту процессора (рис. [-@fig:014]).

![Частота процессора](image/14.jpg){#fig:014 width=70%}

И модель процессора (рис. [-@fig:015]).

![Модель процессора](image/15.jpg){#fig:015 width=70%}

И количество доступной памяти (рис. [-@fig:016]).

![Доступная память](image/16.jpg){#fig:016 width=70%}

И гепирвизор (рис. [-@fig:017]).

![Гипервизор](image/17.jpg){#fig:017 width=70%}

И порядок монтирования файловых систем вместе с их типами. Тип файловой системы, вероятно, xfs 5 версии (рис. [-@fig:018]).

![Порядок монтирования](image/18.jpg){#fig:018 width=70%}

# Выводы

в результате выполнения работы была установлена система

# Список литературы{.unnumbered}

::: {#refs}
:::
