---
## Front matter
title: "Отчет по лабораторной работе №4"
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

Реализовать математическую модель гармонического осциллятора.

# Задание

Постройте фазовый портрет гармонического осциллятора и решение уравнения гармонического осциллятора для следующих случаев

![](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab4/report/image/0.png){#fig:001 width=90%}

# Выполнение лабораторной работы

1. Построила модель колебания гармонического осциллятора без затуханий и без действий внешней силы на языке Julia.

![*Код на языке Julia*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab4/report/image/1.png){#fig:002 width=70%}

![*Решение уравнения гармонического осциллятора без затуханий и без действий внешней силы*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab4/report/image/2.png){#fig:003 width=70%}

![*Фазовый портрет гармонического осциллятора без затуханий и без действий внешней силы*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab4/report/image/3.png){#fig:004 width=70%}

2. Построила ту же модель на языке OpenModelica.

![*Код на языке OpenModelica*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab4/report/image/4.png){#fig:005 width=70%}

![*Решение уравнения гармонического осциллятора без затуханий и без действий внешней силы*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab4/report/image/5.png){#fig:006 width=70%}

![*Фазовый портрет гармонического осциллятора без затуханий и без действий внешней силы*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab4/report/image/6.png){#fig:007 width=70%}

3. Построила модель колебания гармонического осциллятора c затуханием и без действий внешней силы на языке Julia.

![*Код на языке Julia*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab4/report/image/7.png){#fig:008 width=70%}

![*Решение уравнения гармонического осциллятора c затуханием и без действий внешней силы*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab4/report/image/8.png){#fig:009 width=70%}

![*Фазовый портрет гармонического осциллятора c затуханием и без действий внешней силы*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab4/report/image/9.png){#fig:010 width=70%}

4. Построила ту же модель на языке OpenModelica.

![*Код на языке OpenModelica*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab4/report/image/10.png){#fig:011 width=70%}

![*Решение уравнения гармонического осциллятора c затуханием и без действий внешней силы*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab4/report/image/11.png){#fig:012 width=70%}

![*Фазовый портрет гармонического осциллятора c затуханием и без действий внешней силы*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab4/report/image/12.png){#fig:013 width=70%}

5. Построила модель колебания гармонического осциллятора c затуханием и под действием внешней силы на языке Julia.

![*Код на языке Julia*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab4/report/image/13.png){#fig:014 width=70%}

![*Решение уравнения гармонического осциллятора c затуханием и под действием внешней силы*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab4/report/image/14.png){#fig:015 width=70%}

![*Фазовый портрет гармонического осциллятора c затуханием и под действием внешней силы*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab4/report/image/15.png){#fig:016 width=70%}

6. Построила ту же модель на языке OpenModelica.

![*Код на языке OpenModelica*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab4/report/image/16.png){#fig:017 width=70%}

![*Решение уравнения гармонического осциллятора c затуханием и под действием внешней силы*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab4/report/image/17.png){#fig:018 width=70%}

![*Фазовый портрет гармонического осциллятора c затуханием и под действием внешней силы*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab4/report/image/18.png){#fig:019 width=70%}

# Выводы

Я реализовала математическую модель гармонического осциллятора.

# Список литературы{.unnumbered}

::: {#refs}
:::
