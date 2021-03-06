---
## Front matter
lang: ru-RU
title: Structural approach to the deep learning method
author: Дмитриев Александр Дмитриевич 
institute: RUDN University, Moscow, Russian Federation
date: 01 июня 2021

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

## Презентация по лабораторной работе номер 13

# Цель выполнения лабораторной работы 

Изучить основы программирования в оболочке ОС UNIX. Научиться писать более сложные командные файлы с использованием логических управляющих конструкций и циклов.

# Задачи выполнения лабораторной работы

1. Написать командный файл, реализующий упрощённый механизм семафоров. Командный файл должен в течение некоторого времени t1 дожидаться освобождения ресурса, выдавая об этом сообщение, а дождавшись его освобождения, использовать его в течение некоторого времени, также выдавая информацию о том, что ресурс используется соответствующим командным файлом.
2. Реализовать команду man с помощью командного файла. Изучите содержимое каталога /usr/share/man/man1. 
3. Использовать встроенную переменную $RANDOM и написать командный файл, генерирующий случайную последовательность букв латинского алфавита.

# Результаты выполнения лабораторной работы

В ходе выполнения данной лабораторной работы я изучил основы программирования в оболочке ОС UNIX, а также научился писать более сложные командные файлы с использованием логических управляющих
конструкций и циклов.