---
## Front matter
lang: ru-RU
title: "Презентация по лабораторной работе №6"
subtitle: "Дисциплина: Математическое моделирование"
author:
  - Лобанова П.И.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 11 апреля 2025

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

Реализовать модель эпидемии.

# Задание

На одном острове вспыхнула эпидемия. Известно, что из всех проживающих на острове (N=12 400) в момент начала эпидемии (t=0) число заболевших людей (являющихся распространителями инфекции) I(0)=150, А число здоровых людей с иммунитетом к болезни R(0)=55. Таким образом, число людей восприимчивых к болезни, но пока здоровых, в начальный момент времени S(0)=N-I(0)- R(0). 
Постройте графики изменения числа особей в каждой из трех групп. Рассмотрите, как будет протекать эпидемия в случае:
1) если I(0) <= I*
2) если I(0) > I*

# Выполнение

![*Код на языке Julia*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab6/report/image/1.png){#fig:001 width=70%}

## 

![*График изменения числа особей в каждой из трех групп (при I(0) <= I*)*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab6/report/image/2.png){#fig:002 width=70%}

## 

![*Код на языке OpenModelica*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab6/report/image/3.png){#fig:003 width=70%}

## 

![*График изменения числа особей в каждой из трех групп (при I(0) <= I*)*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab6/report/image/4.png){#fig:004 width=70%}

## 

![*Код на языке Julia*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab6/report/image/5.png){#fig:005 width=70%}

## 

![*График изменения числа особей в каждой из трех групп (при I(0) > I*)*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab6/report/image/6.png){#fig:006 width=70%}

## 

![*Код на языке OpenModelica*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab6/report/image/7.png){#fig:007 width=70%}

## 

![*График изменения числа особей в каждой из трех групп при (I(0) > I*)*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab6/report/image/8.png){#fig:008 width=70%}

# Вывод

Я реализовала модель эпидемии.


