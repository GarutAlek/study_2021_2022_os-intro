---
## Front matter
title: "Индивидуальный проект"
subtitle: "Этап 2"
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

Добавить информации о себе, написать несколько постов на своём github pages.

# Ход работы

1. Изменим картинку

Просто поменяем avatar.jpg на своё изображение

![image1](image/1.png){ width=100% }
*Изображение1: Замена картинки*

2. Добавим информации о себе

Напишем кратко информацию в биографию, добавим увлечения и информацию об образовании.

![image2](image/2.png){ width=100% }
*Изображение2: Изменённый вариант*


3. Напишем пост о прошедшей неделе

Напишем пост, согласно шаблону, оставленному нам преподавателем.

![image3](image/3.png){ width=100% }
*Изображение3: Написанный пост о прошедшей неделе*

4. Напишем пост о git

Воспользуемся википедией для создания поста

![image4](image/4.png){ width=100% }
*Изображение4: Написанный пост о git*

# Вывод

На сайт была добавлена информация обо мне и были написаны несколько постов.
