---
## Front matter
title: "Отчёта по лабораторной работе 2"
subtitle: "GitHub and Git"
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

- Изучить идеологию и применение средств контроля версий.
- Освоить умения по работе с git.

# Ход Работы

 Я создал Чётную запись на сайте Github. (рис. [-@fig:001])

![GitHub](image/1.png){ #fig:001 width=70% }

Я установил GitHub на Linux. (рис. [-@fig:002])

![Installation](image/2.png){ #fig:002 width=70% }

Я сделал некоторые настройки. (рис. [-@fig:003])

![Configurations](image/3.png){ #fig:003 width=70% }

Я создал ключ GPG. (рис. [-@fig:004])

![GPG key](image/4.png){ #fig:004 width=70% }

Я создал ключ SSH. (рис. [-@fig:005])

![SSH key](image/5.png){ #fig:005 width=70% }

Я установил эти ключи на моей чётной записью в GitHub. (рис. [-@fig:006])

![SSH and GPG keys on GitHub](image/6.png){ #fig:006 width=70% }

Я клонировал репозиторий в моём компьютере. (рис. [-@fig:007])

![Repository cloned](image/7.png){ #fig:007 width=70% }

Потом, я отправил этот репозиторий в GitHub. (рис. [-@fig:008])

![Repository on GitHub](image/8.png){ #fig:008 width=70% }

# Выводы

-	В ходе этого лабораторного занятия мы получили элементарные знания о системах контроля версий, в частности о GitHub.
