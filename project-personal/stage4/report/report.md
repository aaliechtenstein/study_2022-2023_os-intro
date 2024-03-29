---
## Front matter
title: "ОТЧЕТ О ВЫПОЛНЕНИИ ИНДИВИДУАЛЬНОГО ПРОЕКТА. ЭТАП №4"
subtitle: "_дисциплина: Операционные системы_"
author: "Лихтенштейн Алина Алексеевна"

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
lot: false # List of tables
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
Целью работы является добавление/редактирование основной информации на сайте.

# Задачи
1. Зарегистрироваться на соответствующих ресурсах и разместить на них ссылки на сайте.
2. Сделать пост по прошедшей неделе.
3. Добавить пост на тему по выбору.

# Выполнение лабораторной работы

1. Зарегистрируемся на соответствующих ресурсах и разместим на них ссылки на сайте (рис. [-@fig:001], [-@fig:002])

![Размещение ссылок](image/1.png){#fig:001 width=100%}

![Результат задания №1](image/2.png){#fig:002 width=100%}

2. Сделаем пост по прошедшей неделе (рис. [-@fig:003], [-@fig:004])

![Пост по прошедшей неделе](image/3.png){#fig:003 width=100%}

![Результат задания №2](image/4.png){#fig:004 width=100%}

3. Добавим пост на тему по выбору (рис. [-@fig:005], [-@fig:006])

![Пост на тему по выбору](image/5.png){#fig:005 width=100%}

![Результат задания №3](image/6.png){#fig:006 width=100%}


# Выводы
Были добавлена ссылки на сайте, добавлены посты по прошедшей неделе и теме по выбору

