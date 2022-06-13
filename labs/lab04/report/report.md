---
## Front matter
title: "Отчёта по лабораторной работе 4"
subtitle: "Командна сторки"
author: "Аристид Жан Лоэнс Аристобуль Надаль"

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

- Приобретение практических навыков взаимодействия пользователя с системой по-
средством командной строки.

# Ход Работы

Определил полное имя вашего домашнего каталога (рис. [-@fig:001])

![домашный каталог](image/1.png){ #fig:001 width=70% }

Переместил в каталоге /tmp (рис. [-@fig:002])

![Folder /tmp](image/2.png){ #fig:002 width=70% }

Посмотрел содержание каталога /tmp (рис. [-@fig:003])

![Content /tmp](image/3.png){ #fig:003 width=70% }

Посмотрел Содержание домашнего каталога  (рис. [-@fig:004])

![Содержание домашнего каталога](image/4.png){ #fig:004 width=70% }

Создал каталог newdir при помощи команда mkdir (рис. [-@fig:005])

![Каталог newdir](image/5.png){ #fig:005 width=70% }

Создал подкаталог morefun (рис. [-@fig:006])

![Подкаталог morefun](image/6.png){ #fig:006 width=70% }

Создал каталоги letters memos misk (рис. [-@fig:007])

![Каталоги letters memos misk](image/7.png){ #fig:007 width=70% }

Информациии о команде ls при помощи команда man (рис. [-@fig:008])

![man ls](image/8.png){ #fig:008 width=70% }

Информациии о команде cd, pwd, mkdir, rmdir, rm при помощи команда man (рис. [-@fig:009])

![man cd/ man pwd/ man mkdir ...](image/9.png){ #fig:009 width=70% }

Исползовал команд history (рис. [-@fig:010])

![Command history](image/10.png){ #fig:010 width=70% }

Исползовал конструкци !<Номер_команды> (рис. [-@fig:011])

![!<Номер_команды>](image/11.png){ #fig:011 width=70% }

Исползовал конструкци !<номер_команды>:s/<что_меняем>/<на_что_меняем> (рис. [-@fig:012])

![!<номер_команды>:s/<что_меняем>/<на_что_меняем>](image/12.png){ #fig:012 width=70% }

# Выводы

- В ходе этой лабораторной работы мы научились взаимодействовать с системой через строки команд для вызова из терминала.


