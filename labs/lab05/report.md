---
## Front matter
title: "Лабораторная работа №4."
subtitle: "Дискреционное разграничение прав в Linux. Расширенные атрибуты."
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

Получение практических навыков работы в консоли с расширенными атрибутами файлов.

# Теоретическое введение

Rocky Linux — дистрибутив Linux, разработанный Rocky Enterprise Software Foundation. Предполагается, что это будет полный бинарно-совместимый выпуск, использующий исходный код операционной системы Red Hat Enterprise Linux (RHEL). Цель проекта — предоставить корпоративную операционную систему производственного уровня, поддерживаемую сообществом. Rocky Linux, наряду с Red Hat Enterprise Linux и SUSE Linux Enterprise, стала популярной для использования в корпоративных операционных системах.

Первая версия-кандидат на выпуск Rocky Linux была выпущена 30 апреля 2021 г., а ее первая общедоступная версия была выпущена 21 июня 2021 г. Rocky Linux 8 будет поддерживаться до мая 2029 г.

# Выполнение работы

1. Установим расширенный атрибут a на файл file1.

![установка расширенного атрибута a на файл](image/1.png){#fig:001 width=70%}

2. Попробуем дозаписать в файл новую информацию с помощью команды echo.

![запись в файл новой информации](image/2.png){#fig:001 width=70%}

3. Попробуем изменить содержимое файла, переименовать его, поменять атрибуты файла, получим отказ в доступе.

![отказ в доступе при выполнении некоторых операций](image/3.png){#fig:001 width=70%}

4. Снимем расширенный атрибут файла.

![снятие расширенного атрибута файла](image/4.png){#fig:001 width=70%}

5. Попробуем сделать предыдущие команды, без расширенного атрибута файла.

![команды без расширенного атрибута файла](image/5.png){#fig:001 width=70%}

6. Добавим расширенный атрибут файла i.

![добавление расширенного атрибута файла i](image/6.png){#fig:001 width=70%}

7. Попробуем исполнить предыдущие команды с расширенным атрибутом i, получим отказ в доступе при попытках изменить содержимое файла, переименовать файл.

![исполнение команды расширенного атрибута файла i](image/7.png){#fig:001 width=70%}
# Выводы

Я получил практические навыки работы в консоли с расширенными атрибутами файлов.

# Список литературы{.unnumbered}

Кулябов Д.С. "Материалы к лабораторным работам"
