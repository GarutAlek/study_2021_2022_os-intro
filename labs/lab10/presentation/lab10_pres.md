---
## Front matter
lang: ru-RU
title: Программирование в командном процессоре ОС UNIX. Командные файлы
author: |
	Alexandr I. Garut\inst{1}
institute: |
	\inst{1}RUDN University, Moscow, Russian Federation
date: 2022, 01 May

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
---

## Цель работы

Изучить основы программирования в оболочке ОС UNIX/Linux. Научиться писать небольшие командные файлы.

## Ход работы

1. Напишем скрипт, который при запуске делает резервную копию себя, в backup в домашнем каталоге, архивируя себя.
2. Напишем скрипт, принимающий произвольное число аргуметнов, выводящий их же.
3. Напишем скрипт, аналог ls, который выводит файлы из директории и их права доступа.
4. Напишем скрипт, который выводит количество файлов заданного разрешения в заданной диретории.

## Вывод

Изучили основы программирования в оболочке ОС UNIX/Linux. Научились писать небольшие командные файлы.