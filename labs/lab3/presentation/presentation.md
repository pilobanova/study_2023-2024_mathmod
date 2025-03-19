---
## Front matter
lang: ru-RU
title: "Презентация по лабораторной работе №3"
subtitle: "Дисциплина: Математическое моделирование"
author:
  - Лобанова П.И.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 19 марта 2025

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Докладчик


  * Лобанова Полина Иннокентьевна
  * Учащаяся на направлении "Фундаментальная информатика и информационные технологии"
  * Студентка группы НФИбд-02-22
  * [polla-2004@mail.ru](polla-2004@mail.ru)

# Цель

Реализовать модель боевых действий на языках OpenModelica и Julia.

# Задание

Между страной Х и страной У идет война. Численность состава войск исчисляется от начала войны, и являются временными функциями x(t) и y(t). В начальный момент времени страна Х имеет армию численностью 22 022 человек, а в распоряжении страны У армия численностью в 33 033 человек. Для упрощения модели считаем, что коэффициенты a, b, c, h постоянны. Также считаем P(t) и Q(t) непрерывные функции.
Постройте графики изменения численности войск армии Х и армии У для следующих случаев:

![*Случай 1*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab3/report/image/1.png){#fig:001 width=50%}

##

![*Случай 2*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab3/report/image/2.png){#fig:002 width=50%}

# Выполнение 

![*Программа для боевых действий между регулярными войсками на языке Julia*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab3/report/image/3.png){#fig:003 width=70%}

##

![*График модели боевых действий между регулярными войсками*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab3/report/image/4.png){#fig:004 width=70%}

## 

![*Программа для боевых действий между регулярными войсками на языке OpenModelica*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab3/report/image/5.png){#fig:005 width=70%}

## 

![*График модели боевых действий между регулярными войсками*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab3/report/image/6.png){#fig:006 width=70%}

## 

![*Программа для боевых действий с участием регулярных войск и партизанских отрядов на языке Julia*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab3/report/image/7.png){#fig:007 width=70%}

## 

![*График модели боевых действий с участием регулярных войск и партизанских отрядов*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab3/report/image/8.png){#fig:008 width=70%}

## 

![*Программа для боевых действий с участием регулярных войск и партизанских отрядов на языке OpenModelica*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab3/report/image/9.png){#fig:009 width=50%}

## 
![*График модели боевых действий с участием регулярных войск и партизанских отрядов*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab3/report/image/10.png){#fig:0010 width=70%}

# Вывод

Я реализовала модель боевых действий на языках OpenModelica и Julia.


