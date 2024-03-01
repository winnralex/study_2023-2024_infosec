---
## Front matter
title: "Индивидуальный проект этап 1"
subtitle: "Установка Kali Linux"
author: "Александр Андреевич Шуплецов"

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
lot: true # List of tables
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

Установить дистрибутив Kali Linux в виртуальную машину, произвести первоначальную настройку.

# Выполнение работы

1. Установим нужную версию Kali Linux с официального сайта.

![установка нужной версии Kali Linux](image/1.png){#fig:001 width=70%}

2. Распакуем архив, загруженный с официального сайта Kali Linux.

![распаковка архива](image/2.png){#fig:001 width=70%}

3. Настроим Kali Linux в виртуальной машине.

![настройка Kali Linux в виртуальной машине](image/3.png){#fig:001 width=70%}

4. Осуществим первый запуск Kali Linux.

![первый запуск Kali Linux](image/4.png){#fig:001 width=70%}

5. Осуществим первый вход в систему, используя логин и пароль kali.

![первый вход в систему](image/5.png){#fig:001 width=70%}

6. Установим образ диска дополнений гостевой ОС.

![установка образа диска дополнений гостевой ОС](image/6.png){#fig:001 width=70%}

# Выводы

Я установил дистрибутив Kali Linux в виртуальную машину, произвел первоначальную настройку.

# Список литературы{.unnumbered}

Кулябов Д.С. "Материалы к учебному проекту"
