---
## Front matter
title: "Отчёт по лабораторной работе 4"
subtitle: "Markdown"
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

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown.

# Ход Работы

Мы написали отчёт по Лаб01 на формате markdown (рис. [-@fig:001])

![Report lab 1 in md](image/1.png){ #fig:001 width=70% }

мы создали формат pdf и docx из md по отчёту Лаб01 (рис. [-@fig:002])

![Format pdf and docx ReportLab1](image/2.png){ #fig:002 width=70% }

Мы написали презентацию по Лаб01 на формате markdown (рис. [-@fig:003])

![Presentation lab 1 in md](image/3.png){ #fig:003 width=70% }

Мы написали отчёт по Лаб02 на формате markdown (рис. [-@fig:004])

![Report lab 2 in md](image/4.png){ #fig:004 width=70% }

мы создали формат pdf и docx из md по отчёту Лаб02 (рис. [-@fig:005])

![Format pdf and docx ReportLab2](image/5.png){ #fig:005 width=70% }

Мы написали презентацию по Лаб02 на формате markdown (рис. [-@fig:006])

![Presentation lab 2 in md](image/6.png){ #fig:006 width=70% }

# Выводы

В ходе этой лабораторной работы мы научились записывать файлы в формате уценки и преобразовывать их в pdf и docx.

