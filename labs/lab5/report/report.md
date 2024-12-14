---
## Front matter
title: "Лабораторная работа № 5"
subtitle: "Построение графиков"
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
Оновная цель работы — освоить синтаксис языка Julia для построения графиков.

# Задание
1. Используя Jupyter Lab, повторите примеры из раздела 5.2. При этом дополните графики
обозначениями осей координат, легендой с названиями траекторий, названиями
графиков и т.п.
2. Выполните задания для самостоятельной работы (раздел 5.4)

# Выполнение лабораторной работы
![часть 1](image/1.png)
![часть 2](image/2.png)
![часть 3](image/3.png)
![часть 4](image/4.png)
![часть 5](image/5.png)
![часть 6](image/6.png)
![часть 7](image/7.png)
![часть 8](image/8.png)
![часть 9](image/9.png)
![часть 10](image/10.png)
![часть 11](image/11.png)
![часть 12](image/12.png)
![часть 13](image/13.png)
![часть 14](image/14.png)


# Выводы
Я освоил синтаксис языка Julia для построения графиков.

# Список литературы{.unnumbered}
