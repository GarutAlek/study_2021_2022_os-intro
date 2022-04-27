---
## Front matter
title: "Лабораторная работа 6"
subtitle: "Поиск файлов. Перенаправление ввода-вывода. Просмотр запущенных процессов"
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

Ознакомление с инструментами поиска файлов и фильтрации текстовых данных.
Приобретение практических навыков: по управлению процессами (и заданиями), по
проверке использования диска и обслуживанию файловых систем.

# Ход работы

1. Создание файла file.txt и запись в него названий файлов содержащихся в каталоге /etc и в домашнем каталоге

![image1](image/1.png){ width=100% }
*Изображение1: Запись в file.txt требуемых названий файлов*

2. Вывод имён файлов заканчивающихся на ".conf" в файл conf.txt

![image2](image/2.png){ width=100% }
*Изображение2: Запись в файл conf.txt*

3. Выполнение пунктов 4 и 5 лабораторной работы

![image3.1](image/3.1.png){ width=100% }
*Изображение3.1: Пункт 4 лабораторной работы*

![image3.2](image/3.2.png){ width=100% }
*Изображение3.2: Пункт 5 лабораторной работы*

4. Запуск в фоновом режиме процесса, записывающего в файл ~/logfile все имена начинающиеся на "log", а так же удаление файла logfile

![image4.1](image/4.1.png){ width=100% }
*Изображение4.1: Запуск в фоновом режиме процесса, записывающего в файл ~/logfile все имена начинающиеся на "log"*

![image4.2](image/4.2.png){ width=100% }
*Изображение4.2: Удаление файла logfile*

5. Запуск gedit в фоновом режиме, а так же завершение этого процесса

![image5.1](image/5.1.png){ width=100% }
*Изображение5.1: Запуск gedit в фоновом режиме*

![image5.2](image/5.2.png){ width=100% }
*Изображение5.2: Завершение фонового процесса gedit*

6. Выполнение пункта 12 Лабораторной работы

![image6](image/6.png){ width=100% }
*Изображение6: Вывод имён всех директорий, имеющихся в моём домашнем каталоге*

# Вывод

Ознакомились с инструментами поиска файлов и фильтрации текстовых данных. Приобрели практические навыки по управлению процессами (и заданиями), по проверке использования диска, и обслуживанию файловых систем.

# Контрольные вопросы

1. 
– stdin — стандартный поток ввода (по умолчанию: клавиатура), файловый дескриптор
0;

– stdout — стандартный поток вывода (по умолчанию: консоль), файловый дескриптор
1;

– stderr — стандартный поток вывод сообщений об ошибках (по умолчанию: консоль),
файловый дескриптор 2.

2. ">" - это открывает файл на перезапись, когда ">>" открывает файл на дозапись

3. Направление вывода на вход для следующей команды

4. Процесс - это исполняемая программа.

Программа - это набор инструкций, которые выполняют определенную задачу при выполнении компьютером, в то время как процесс является экземпляром выполняемой компьютерной программы. Таким образом, в этом главное отличие программы и процесса.

5. pid: это идентификатор процесса (PID) процесса, который вы вызываете

GID: идентификатор группы. Все группы Linux определяются GID (идентификаторами групп). GID хранятся в файле / etc / groups.
