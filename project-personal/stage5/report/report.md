---
## Front matter
title: "Отчёт по пятому этапу итогового проекта"
subtitle: "Специальность: архитектура компьютеов"
author: "Кудинец Максим Антонович"

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

Добавить с сайту все остальные элементы.

# Задание

1. Сделать записи для персональных проектов.
2. Сделать пост по прошедшей неделе.
3. Добавить пост на тему: Языки научного программирования.

# Теоретическое введение

# Выполнение лабораторной работы

1. Оформляем файл с записями для персональных проектов, удаляем лищние файлы при необходимости. (рис. [-@fig:001])

![Переоформленный файл](image/report1.jpg){#fig:001 width=70%}

2. Делаем изменения на сервере. (рис. [-@fig:002])

![Изменения на сервере](image/report2.jpg){#fig:002 width=70%}

3. Делаем пост о прошедшей неделе. (рис. [-@fig:003])

![Пост о прошедшей неделе](image/report3.jpg){#fig:003 width=70%}

4. Выкладываем на сайт. (рис. [-@fig:004])

![Изменения на сайте](image/report4.jpg){#fig:004 width=70%}

5. Делаем пост на тему по выбору. (рис. [-@fig:005])

![Пост по теме "Языки научного программирования"](image/report5.jpg){#fig:005 width=70%}

6. Выкладываем на сайт. (рис. [-@fig:006])

![Выложенный на сайт пост](image/report6.jpg){#fig:006 width=70%}

# Выводы

Добавил к сайту необходимые изменения, настроил вкладку с проектами.

# Список литературы{.unnumbered}

::: {#refs}
:::
