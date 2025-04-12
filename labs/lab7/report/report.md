---
## Front matter
title: "Отчет по лабораторной работе №7"
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

Построить график распространения рекламы.

# Задание

Постройте график распространения рекламы, математическая модель которой описывается
следующим уравнением:

![](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab7/report/image/0.png){#fig:000 width=70%}

При этом объем аудитории N = 1040, в начальный момент о товаре знает 9 человек. Для
случая 2 определите в какой момент времени скорость распространения рекламы будет иметь максимальное значение.

# Выполнение лабораторной работы

1. Написала программу для построения графика первого случая на языке Julia.

![*Код на языке Julia для случая 1*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab7/report/image/1.png){#fig:001 width=70%}

![*График распространения рекламы (случай 1)*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab7/report/image/2.png){#fig:002 width=70%}

2. Написала программу для построения графика первого случая на языке OpenModelica.

![*Код на языке OpenModelica для случая 1*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab7/report/image/8.png){#fig:003 width=70%}

![*График распространения рекламы (случай 1)*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab7/report/image/9.png){#fig:004 width=70%}

3. Написала программу для построения графика второго случая на языке Julia.

![*График распространения рекламы (случай 2)*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab7/report/image/3.png){#fig:005 width=70%}

4. Написала программу для построения графика второго случая на языке OpenModelica.

![*Код на языке OpenModelica для случая 2*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab7/report/image/4.png){#fig:006 width=70%}

![*График распространения рекламы (случай 2)*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab7/report/image/5.png){#fig:007 width=70%}

5. Для случая 2 определила в какой момент времени скорость распространения рекламы будет иметь максимальное значение. 

![*Код на языке Julia для вычисления максимального значения*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab7/report/image/10.png){#fig:008 width=70%}

![*График распространения рекламы (случай 2) и максимальное значение*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab7/report/image/11.png){#fig:009 width=70%}

6. Написала программу для построения графика третьего случая на языке Julia.

![*Код на языке Julia для случая 3*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab7/report/image/6.png){#fig:010 width=70%}

![*График распространения рекламы (случай 3)*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab7/report/image/7.png){#fig:011 width=70%}

7. Написала программу для построения графика третьего случая на языке OpenModelica.

![*Код на языке OpenModelica для случая 3*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab7/report/image/12.png){#fig:012 width=70%}

![*График распространения рекламы (случай 3)*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab7/report/image/13.png){#fig:013 width=70%}


# Выводы

Я построила график распространения рекламы.

# Список литературы{.unnumbered}

::: {#refs}
:::
