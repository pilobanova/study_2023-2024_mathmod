---
## Front matter
title: "Отчет по лабораторной работе №1"
subtitle: "Дисциплина: Математическое моделирование"
author: "Лобанова Полина Иннокентьевна"

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

Научиться работать  с git и Markdown.


# Выполнение лабораторной работы

1. Создала новый репозиторий по шаблону.

![*Созданный репозиторий*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab1/report/image/лаб1/1.png){#fig:001 width=70%}

2. Клонировала его.

![*Клонирование*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab1/report/image/лаб1/2.png){#fig:002 width=70%}

3. Добавила файлы для создания отчетов и отправила файлы на сервер.

![*Отправка на сервер*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab1/report/image/лаб1/3.png){#fig:003 width=70%}

![*Отправка на сервер*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab1/report/image/лаб1/4.png){#fig:004 width=70%}

# Выводы

Я научилась работать  с git и Markdown.

