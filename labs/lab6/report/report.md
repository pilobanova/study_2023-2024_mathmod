---
## Front matter
title: "Отчет по лабораторной работе №6"
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

Реализовать модель эпидемии.

# Задание

На одном острове вспыхнула эпидемия. Известно, что из всех проживающих на острове (N=12 400) в момент начала эпидемии (t=0) число заболевших людей (являющихся распространителями инфекции) I(0)=150, А число здоровых людей с иммунитетом к болезни R(0)=55. Таким образом, число людей восприимчивых к болезни, но пока здоровых, в начальный момент времени S(0)=N-I(0)- R(0). 
Постройте графики изменения числа особей в каждой из трех групп. Рассмотрите, как будет протекать эпидемия в случае:
1) если I(0) <= I*
2) если I(0) > I*


# Выполнение лабораторной работы

1. Построила график модели при I(0) <= I* на языке Julia.

![*Код на языке Julia*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab6/report/image/1.png){#fig:001 width=70%}

![*График изменения числа особей в каждой из трех групп (при I(0) <= I*)*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab6/report/image/2.png){#fig:002 width=70%}

2. Построила график модели при I(0) <= I* на языке OpenModelica.

![*Код на языке OpenModelica*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab6/report/image/3.png){#fig:003 width=70%}

![*График изменения числа особей в каждой из трех групп (при I(0) <= I*)*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab6/report/image/4.png){#fig:004 width=70%}

3. Построила график модели при I(0) > I* на языке Julia.

![*Код на языке Julia*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab6/report/image/5.png){#fig:005 width=70%}

![*График изменения числа особей в каждой из трех групп (при I(0) > I*)*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab6/report/image/6.png){#fig:006 width=70%}

4. Построила график модели при I(0) > I* на языке OpenModelica.

![*Код на языке OpenModelica*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab6/report/image/7.png){#fig:007 width=70%}

![*График изменения числа особей в каждой из трех групп при (I(0) > I*)*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab6/report/image/8.png){#fig:008 width=70%}


# Выводы

Я реализовала модель эпидемии.

# Список литературы{.unnumbered}

::: {#refs}
:::
