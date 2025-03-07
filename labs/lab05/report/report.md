---
## Front matter
title: "Отчёт по лабораторной работе №5"
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

Установить, настроить и научиться пользоваться основными возможностями менеджера паролей

# Задание

1. Установка и настройка менеджера паролей
2. Управление файлами конфигурации
3. Установка дополнительного программного обеспечения

# Выполнение лабораторной работы

1. Создание репозитория для хранения паролей и использования основных команд (рис. [-@fig:001]).

![Репозиторий](image/report1.jpg){#fig:001 width=70%}

2. Установка и инициализация программы pass (рис. [-@fig:009]).

![Программа pass](image/report9.jpg){#fig:009 width=70%}

3. Создание нового каталога, (рис. [-@fig:007]). загрузка в него пароля, (рис. [-@fig:005]). генерация нового пароля и установка дополнительного программного обеспечения (рис. [-@fig:006]). и шрифтов (рис. [-@fig:002]).

![Новый каталог](image/report7.jpg){#fig:007 width=70%}

![Загрузка пароля в каталог](image/report5.jpg){#fig:005 width=70%}

![Генерация нового пароля и доп программное обеспечение](image/report6.jpg){#fig:006 width=70%}

![Настройка шрифтов](image/report2.jpg){#fig:002 width=70%}

4. Установка бинарного файла, клонирование шаблонного репозитория (рис. [-@fig:004]).

![Бинарный файл и клонирование репозитория](image/report4.jpg){#fig:004 width=70%}

5. Настройка chezmoi, (рис. [-@fig:003]). проверка изменений, (рис. [-@fig:008]). установка своих dotfiles на новый компьютер (рис. [-@fig:010]).

![Настройка](image/report3.jpg){#fig:003 width=70%}

![Проверка изменений](image/report8.jpg){#fig:008 width=70%}

![Проверка команды для нового пк](image/report10.jpg){#fig:010 width=70%}

# Выводы

Разобрался с работой менеджера паролей и научился пользоваться основными его командами

# Список литературы{.unnumbered}

::: {#refs}
:::
