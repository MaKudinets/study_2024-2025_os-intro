---
## Front matter
title: "Отчёт по третьему этапу итогового проекта"
subtitle: "Специальность: архитерктура компьютеров"
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

Добавить к сайту достижения.

# Задание

1. Добавить к сайту достижения:
Добавить информацию о навыках (Skills).
Добавить информацию об опыте (Experience).
Добавить информацию о достижениях (Accomplishments).
2. Сделать пост по прошедшей неделе.
3. Добавить пост на тему: Легковесные языки разметки.

# Выполнение лабораторной работы

1. Добавляем в файл необходимую информацию о навыках, достижениях и опыте. (рис. [-@fig:001]).

![Обновленный файл](image/report1.png){#fig:001 width=70%}

2.  Выгружаем информацию на сайт. (рис. [-@fig:002]).

![Новая информация на сайте](image/report2.png){#fig:002 width=70%}

3. Создаём пост на выбранную тему. (рис. [-@fig:003]).

![Пост на тему "Легковесные языки программирования"](image/report3.png){#fig:003 width=70%}

4. Выкладываем пост на сайт. (рис. [-@fig:004]).

![Выложенный на сайт пост](image/report4.png){#fig:004 width=70%}

5. Создаем пост о прошлой неделе. (рис. [-@fig:005]).

![Пост о прошлой неделе](image/report5.png){#fig:005 width=70%}

6. Выкладываем пост на сайт. (рис. [-@fig:006]).

![Выложенный на сайт пост](image/report6.png){#fig:006 width=70%}

# Выводы

Добавил к сайту необходимую информацию, сделал 2 поста.

# Список литературы{.unnumbered}

::: {#refs}
:::
