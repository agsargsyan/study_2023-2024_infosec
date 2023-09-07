---
## Front matter
title: "Отчёт по лабораторной работе №1"
subtitle: "Первоначальная настройка оборудования"
author: "Саргсян Арам Грачьяевич"

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

Установка виртуальной машины rocky 9 linux для дальнейшей работы

# Выполнение лабораторной работы

1. Я скачал rocky 9 linux c официального сайта, задал конфигурацию жёсткого диска — VDI, виделил 40 гб памяти (рис. @fig:001).
  
![Основные настройки](image/lab1_1.png){ #fig:001 width=70% height=70% }

2. Подключил образ диска дополнительной гостевой ОС(рис. @fig:002).

![Образ диска гостевой ОС](image/lab1_2.png){ #fig:002 width=70% height=70% }

3. Синхронизировал рабочую папку с репозиторием на github (рис. @fig:003).  

![Репозиторий на github](image/lab1_3.png){ #fig:003 width=70% height=70% }

4. Настроил основные опции git (рис. @fig:004). 

![Команды git](image/lab1_4.png){ #fig:004 width=70% height=70% }

# Выводы

Я установили виртуальную машину, синхронизировал её с моей учетной записью в github для дальнейшей работы с ней.

