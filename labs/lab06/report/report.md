---
## Front matter
title: "Отчёт по лабораторной работе №6"
subtitle: "Специальность: архитектура компьютеров"
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

Приобретение практических навыков взаимодействия пользователя с системой по-
средством командной строки.

# Задачи

1. Разобраться с принципом работы команд cd, mkdir, rm, man и history

# Выполнение лабораторной работы


1. Узнаю полное название своего домашнего каталога. Перехожу в каталог tmp и вывожу на экран его содержимое. (рис. [-@fig:001]).

![Функция 1](image/1.jpg){#fig:001 width=70%}

2. Выполняю действия с каталогами, такие как создание, переход и рекурсивное удаление (рис. [-@fig:002]). (рис. [-@fig:003]).

![Действия с каталогами и файлами](image/2.jpg){#fig:002 width=70%}

![Рекурсивное удаление каталога](image/3.jpg){#fig:003 width=70%}

3. Разбираюсь со способами использования команды man (рис. [-@fig:004]).

![применение команды](image/4.jpg){#fig:004 width=70%}

4. Команда history (рис. [-@fig:005]).

![Использование команды](image/5.jpg){#fig:005 width=70%}

# Выводы

Приобретение практических навыков взаимодействия пользователя с системой по-
средством командной строки.

# Список литературы{.unnumbered}

::: {#refs}
:::
