---
## Front matter
title: "Отчет по лабораторной работе №3"
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

Реализовать модель боевых действий на языках OpenModelica и Julia.

# Задание

Между страной Х и страной У идет война. Численность состава войск исчисляется от начала войны, и являются временными функциями x(t) и y(t). В начальный момент времени страна Х имеет армию численностью 22 022 человек, а в распоряжении страны У армия численностью в 33 033 человек. Для упрощения модели считаем, что коэффициенты a, b, c, h постоянны. Также считаем P(t) и Q(t) непрерывные функции.
Постройте графики изменения численности войск армии Х и армии У для следующих случаев:

![*Случай 1*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab3/report/image/1.png){#fig:001 width=70%}

![*Случай 2*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab3/report/image/2.png){#fig:002 width=70%}

# Выполнение лабораторной работы

1. Написала программу для построения графика модели боевых действий между регулярными войсками на языке Julia. В результате видим, что выигрывает армия У.

![*Программа для боевых действий между регулярными войсками на языке Julia*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab3/report/image/3.png){#fig:003 width=70%}

![*График модели боевых действий между регулярными войсками*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab3/report/image/4.png){#fig:004 width=70%}

2. Написала программу для построения графика модели боевых действий между регулярными войсками на языке OpenModelica. Результат совпадает с предыдущим графиком.

![*Программа для боевых действий между регулярными войсками на языке OpenModelica*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab3/report/image/5.png){#fig:005 width=70%}

![*График модели боевых действий между регулярными войсками*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab3/report/image/6.png){#fig:006 width=70%}

3. Написала программу для построения графика модели боевых действий с участием регулярных войск и партизанских отрядов на языке Julia. В данном случае побеждает армия Х, а численность армии У падает до нуля почти моментально.

![*Программа для боевых действий с участием регулярных войск и партизанских отрядов на языке Julia*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab3/report/image/7.png){#fig:007 width=70%}

![*График модели боевых действий с участием регулярных войск и партизанских отрядов*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab3/report/image/8.png){#fig:008 width=70%}

4. Написала программу для построения графика модели боевых действий с участием регулярных войск и партизанских отрядов на языке OpenModelica. Результат такой же.

![*Программа для боевых действий с участием регулярных войск и партизанских отрядов на языке OpenModelica*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab3/report/image/9.png){#fig:009 width=70%}

![*График модели боевых действий с участием регулярных войск и партизанских отрядов*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab3/report/image/10.png){#fig:0010 width=70%}

# Выводы

Я реализовала модель боевых действий на языках OpenModelica и Julia.

# Список литературы{.unnumbered}

::: {#refs}
:::
