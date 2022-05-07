---
## Front matter
title: "Лабораторная работа 11"
subtitle: "Программирование в командном процессоре ОС UNIX. Ветвления и циклы"
author: "Гарут Александр Игоревич"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
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

Изучить основы программирования в оболочке ОС UNIX. Научится писать более сложные командные файлы с использованием логических управляющих конструкций и циклов.

# Ход работы

1. Выполним пункт 1 лабораторной работы

![image1.1](image/1.1.png){ width=100% }
*Изображение1.1: Код скрипта*

Удостовермися что всё работает

![image1.2](image/1.2.png){ width=100% }
*Изображение1.2: Запуск срипта*

2. Напишем скрипт который указывает больше нуля, равно нулю или меньше нуля наше число

![image2.1](image/2.1.png){ width=100% }
*Изображение2.1: Код скрипта*

Удостовермися что всё работает

![image2.2](image/2.2.png){ width=100% }
*Изображение2.2: Запуск срипта*

3. Напишем скрипт, создающий и удалающий tmp файлы в указанном нами количестве

![image3.1](image/3.1.png){ width=100% }
*Изображение3.1: Код скрипта*

Удостовермися что всё работает

![image3.2](image/3.2.png){ width=100% }
*Изображение3.2: Запуск срипта*

4. Напишем скрипт, архивирующий недавно изменённые файлы

![image4.1](image/4.1.png){ width=100% }
*Изображение4.1: Код скрипта*

Удостовермися что всё работает

![image4.2](image/4.2.png){ width=100% }
*Изображение4.2: Запуск срипта*

# Вывод

Изучили основы программирования в оболочке ОС UNIX. Научились писать более сложные командные файлы с использованием логических управляющих конструкций и циклов.

# Контрольные вопросы

1. Команда getopts возвращает нулевой код завершения, если опция найдена. Если в командной строке больше не остается аргументов или же текущий аргумент не начинается с дефиса, getopts возвращает ненулевой код завершения.

2. При генерации имен используют метасимволы: *, произвольная (возможно пустая) последовательность символов

