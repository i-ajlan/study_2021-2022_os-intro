---
## Front matter
title: "Отчёт по лабораторной работе 11"
subtitle: "Ветвления и циклы"
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

- Изучить основы программирования в оболочке ОС UNIX. 
- Научится писать более сложные командные файлы с использованиемлогических управляющих конструкций и циклов.


# Выполнение лабораторной работы

Использовал команды getopts grep, написал командный файл,который анализирует командную строку с ключами (рис. [-@fig:001])

![First app](image/1.png){ #fig:001 width=70% }

Написал на языке Си программу,которая вводитчисло и определяет,являетсяли оно больше нуля,меньше нуля или равно нулю. (рис. [-@fig:002])

![Second app](image/2.png){ #fig:002 width=70% }

 Написал командный файл,создающий указанное число файлов,пронумерованных последовательно от 1 до 𝑁 (рис. [-@fig:003])

![Third app](image/3.png){ #fig:003 width=70% }

 Написал командный файл,который с помощью команды tar запаковываетв архив все файлы в указанной директории(рис. [-@fig:004])

![Fourth app](image/4.png){ #fig:004 width=70% }

# Выводы

- В ходе этого лабораторного занятия мы углубили свои знания оболочки Linux и создали новые файловые команды.



