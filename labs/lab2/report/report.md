---
## Front matter
title: "Лабораторная работа № 2"
subtitle: "Измерение и тестирование пропускной способности сети. Интерактивный эксперимент"
author: "Старовойтов Егор Сергеевич"

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
Основная цель работы — изучить несколько структур данных, реализованных в Julia,
научиться применять их и операции над ними для решения задач.


# Задание
1. Используя Jupyter Lab, повторите примеры из раздела 2.2.
2. Выполните задания для самостоятельной работы (раздел 2.4)


# Выполнение лабораторной работы
## Задание 1
Были повторены все примеры.

![Кортежи](image/Screenshot_23-Nov_21-59-34_14732.png)

![Словари](image/Screenshot_23-Nov_22-02-09_14137.png)

![Множества](image/Screenshot_23-Nov_22-03-17_27283.png)

![Массивы](image/Screenshot_23-Nov_22-04-30_12718.png)

## Задание 2 - самостоятельная работа
### Задачи 1 и 2
![Задачи 1 и 2](image/Screenshot_23-Nov_22-08-22_2365.png)

### Задача 3
![Часть 1](image/Screenshot_23-Nov_22-27-00_7279.png)

![Часть 2](image/Screenshot_23-Nov_22-27-10_21140.png)

![Часть 3](image/Screenshot_23-Nov_22-27-20_17267.png)

### Задача 4
![Задача 4](image/Screenshot_23-Nov_22-28-29_19112.png)


### Задача 5
![Задача 5](image/Screenshot_23-Nov_22-28-42_8647.png)


### Задача 6
![Задача 6](image/Screenshot_23-Nov_22-28-52_26968.png)


# Выводы
Я изучил несколько структур данных, реализованных в Julia,
научился применять их и операции над ними для решения задач, выполнив все предложенные задания.

# Список литературы{.unnumbered}

