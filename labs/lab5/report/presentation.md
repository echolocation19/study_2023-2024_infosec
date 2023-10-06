---
## Front matter
lang: ru-RU
title: Презентация по лабораторной работе №5
author:
  - Краснова Диана Владимировна
institute:
  - Российский университет дружбы народов, Москва, Россия

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

## Цель лабораторной работы

Изучение механизмов изменения идентификаторов, применения SetUID и Sticky-битов. Получение практических навыков работы в консоли с дополнительными атрибутами. Рассмотрение работы механизма смены идентификатора процессов пользователей, а также влияние бита Sticky на запись и удаление файлов.

# Выполнение лабораторной работы

## Программа simpleid

![результат программы simpleid](image/img2.png){ #fig:001 width=70% height=70%}

## Программа simpleid2

![результат программы simpleid2](image/img5.png){ #fig:002 width=70% height=70%}

## Программа readfile

![результат программы readfile](image/img8.png){ #fig:003 width=70% height=70%}

## Исследование Sticky-бита

![исследование Sticky-бита](image/img10.png){ #fig:004 width=70% height=70%}

# Выводы

## Результаты выполнения лабораторной работы

Изучили механизмы изменения идентификаторов, применения SetUID- и Sticky-битов. Получили практические навыки работы в консоли с дополнительными атрибутами. Также мы рассмотрели работу механизма смены идентификатора процессов пользователей и влияние бита Sticky на запись и удаление файлов