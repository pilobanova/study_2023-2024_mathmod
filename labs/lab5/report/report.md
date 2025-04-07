---
## Front matter
title: "Отчет по лабораторной работе №5"
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

Реализация модели «хищник-жертва».

# Задание

Постройте график зависимости численности хищников от численности жертв, а также графики изменения численности хищников и численности жертв при следующих начальных условиях: x0=8, y0=16. Найдите стационарное состояние системы.

![](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab5/report/image/0.png){#fig:001 width=70%}

# Выполнение лабораторной работы

1. Построила график изменения численности хищников и численности жертв на языке Julia.

![*Код на языке Julia*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab5/report/image/1.png){#fig:002 width=70%}

![*График изменения численности хищников и численности жертв*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab5/report/image/2.png){#fig:003 width=70%}

2. Построила график зависимости численности хищников от численности жертв на языке Julia.

![*График зависимости численности хищников от численности жертв*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab5/report/image/3.png){#fig:004 width=70%}

3. Построила график изменения численности хищников и численности жертв на языке OpenModelica.

![*Код на языке OpenModelica*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab5/report/image/4.png){#fig:005 width=70%}

![*График изменения численности хищников и численности жертв*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab5/report/image/5.png){#fig:006 width=70%}

4. Построила график зависимости численности хищников от численности жертв на языке OpenModelica.

![*График зависимости численности хищников от численности жертв*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab5/report/image/6.png){#fig:007 width=70%}

5. Нашла стационарное состояние системы.

![*Стационарное состояние системы*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab5/report/image/7.png){#fig:008 width=70%}



# Выводы

Я реализовала модель «хищник-жертва».

# Список литературы{.unnumbered}

::: {#refs}
:::
