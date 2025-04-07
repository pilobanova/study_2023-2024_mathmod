---
## Front matter
lang: ru-RU
title: "Презентация по лабораторной работе №5"
subtitle: "Дисциплина: Математическое моделирование"
author:
  - Лобанова П.И.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 7 апреля 2025

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

Реализация модели «хищник-жертва».

# Задание

Постройте график зависимости численности хищников от численности жертв, а также графики изменения численности хищников и численности жертв при следующих начальных условиях: x0=8, y0=16. Найдите стационарное состояние системы.

![](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab5/report/image/0.png){#fig:001 width=70%}


# Выполнение

![*Код на языке Julia*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab5/report/image/1.png){#fig:002 width=70%}

## 

![*График изменения численности хищников и численности жертв*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab5/report/image/2.png){#fig:003 width=70%}

##

![*График зависимости численности хищников от численности жертв*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab5/report/image/3.png){#fig:004 width=70%}

## 

![*Код на языке OpenModelica*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab5/report/image/4.png){#fig:005 width=70%}

## 

![*График изменения численности хищников и численности жертв*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab5/report/image/5.png){#fig:006 width=70%}

## 

![*График зависимости численности хищников от численности жертв*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab5/report/image/6.png){#fig:007 width=70%}

## 

![*Стационарное состояние системы*](/home/pilobanova/work/study/2024-2025/Математическое моделирование/mathmod/labs/lab5/report/image/7.png){#fig:008 width=70%}

# Вывод

Я реализовала модель «хищник-жертва».
