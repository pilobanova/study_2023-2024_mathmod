---
## Front matter
title: "Отчет по лабораторной работе №8"
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

Построить графики изменения оборотных средств фирмы 1 и фирмы 2.

# Задание

Случай 1. Рассмотрим две фирмы, производящие взаимозаменяемые товары одинакового качества и находящиеся в одной рыночной нише. Считаем, что в рамках нашей модели конкурентная борьба ведётся только рыночными методами. То есть, конкуренты могут влиять на противника путем изменения параметров своего производства: себестоимость, время цикла, но не могут прямо вмешиваться в ситуацию на рынке («назначать» цену или влиять на потребителей каким-либо иным способом.) Будем считать, что постоянные издержки пренебрежимо малы, и в модели учитывать не будем. В этом случае динамика изменения объемов продаж фирмы 1 и фирмы 2 описывается следующей системой уравнений:

![](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab8/report/image/20.png){#fig:000 width=70%}

Случай 2. Рассмотрим модель, когда, помимо экономического фактора влияния (изменение себестоимости, производственного цикла, использование кредита и т.п.), используются еще и социально-психологические факторы – формирование общественного предпочтения одного товара другому, не зависимо от их качества и цены. В этом случае взаимодействие двух фирм будет зависеть друг от друга, соответственно коэффициент перед M1M2 будет отличаться. Пусть в рамках рассматриваемой модели динамика изменения объемов продаж фирмы 1 и фирмы 2 описывается следующей системой уравнений:

![](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab8/report/image/0.png){#fig:000 width=70%}

1. Постройте графики изменения оборотных средств фирмы 1 и фирмы 2 без учета постоянных издержек и с веденной нормировкой для случая 1.
2. Постройте графики изменения оборотных средств фирмы 1 и фирмы 2 без учета постоянных издержек и с веденной нормировкой для случая 2.

# Выполнение лабораторной работы

1. Построила график изменения оборотных средств фирмы 1 и фирмы 2 без учета постоянных издержек и с веденной нормировкой для случая 1 на языке Julia.

![*Код на языке Julia для случая 1*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab8/report/image/1.png){#fig:001 width=70%}

![*График изменения оборотных средств фирмы 1 и фирмы 2 (случай 1)*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab8/report/image/2.png){#fig:002 width=70%}

2. Построила графики изменения оборотных средств фирмы 1 и фирмы 2 без учета постоянных издержек и с веденной нормировкой для случая 1 на языке OpenModelica.

![*Код на языке OpenModelica для случая 1*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab8/report/image/3.png){#fig:003 width=70%}

![*График изменения оборотных средств фирмы 1 и фирмы 2 (случай 1)*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab8/report/image/4.png){#fig:004 width=70%}

3. Построила графики изменения оборотных средств фирмы 1 и фирмы 2 без учета постоянных издержек и с веденной нормировкой для случая 2 на языке Julia.

![*Код на языке Julia для случая 2*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab8/report/image/5.png){#fig:005 width=70%}

![*График изменения оборотных средств фирмы 1 и фирмы 2 (случай 2)*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab8/report/image/6.png){#fig:006 width=70%}

4. Построила графики изменения оборотных средств фирмы 1 и фирмы 2 без учета постоянных издержек и с веденной нормировкой для случая 2 на языке OpenModelica.

![*Код на языке OpenModelica для случая 2*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab8/report/image/7.png){#fig:007 width=70%}

![*График изменения оборотных средств фирмы 1 и фирмы 2 (случай 2)*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab8/report/image/8.png){#fig:008 width=70%}

# Выводы

Я построила графики изменения оборотных средств фирмы 1 и фирмы 2.

# Список литературы{.unnumbered}

::: {#refs}
:::
