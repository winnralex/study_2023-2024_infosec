---
## Front matter
title: "Внешний курс раздел 2"
subtitle: "Защита ПК/телефона"
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

Изучить основы защиты данных ПК/телефона.

# Выполнение работы

1. Загрузочный сектор диска, как и другие сектора диска, можно зашифровать.

![первое задание](image/1.png){#fig:001 width=70%}

2. Шифрование диска основано на симметричном шифровании, как правило на алгоритме AES.

![второе задание](image/2.png){#fig:001 width=70%}

3. VeraCrypt и BitLocker - примеры программ, с помощью которых можно зашифровать жесткий диск.

![третье задание](image/3.png){#fig:001 width=70%}

4.  К стойким паролям обычно относят пароли, содержащие большие и маленькие буквы алфавита, цифры, специальные символы, не имеющие реальной смысловой нагрузки, выберем такой пароль из списка.

![четвертое задание](image/4.png){#fig:001 width=70%}

5. Менеджеры паролей являются самым безопасным методом хранения паролей.

![пятое задание](image/5.png){#fig:001 width=70%}

6. Капча нужна для защиты от автоматизированных атак, направленных на получение несанкционированного доступа, она не используется для замены паролей, защиты кук пользователя, безопасного хранения паролей на сервере.

![шестое задание](image/6.png){#fig:001 width=70%}

7. Хэширование паролей нужно для того, чтобы не хранить пароли на сервере в открытом виде, для конфиденциальности паролей пользователей.

![седьмое задание](image/7.png){#fig:001 width=70%}

8. Соль для улучшения стойкости паролей не поможет, если злоумышленник получил доступ к серверу, так как она хранится на сервере.

![восьмое задание](image/8.png){#fig:001 width=70%}

9. Разные пароли на всех сайтах, периодическая смена паролей, сложные пароли, капча защищают от утечек данных атакой перебором. 

![девятое задание](image/9.png){#fig:001 width=70%}

10. Среди представленных ссылок, ссылка для входа в сбербанк и для входа в яндекс являются фишинговыми, так как не имеют никакого отношения к сбербанку и яндексу соответственно.

![десятое задание](image/10.png){#fig:001 width=70%}

11. Фишинговый имейл может прийти от знакомого адреса, этот вид фишинга называется спуфинг.

![одиннадцатое задание](image/11.png){#fig:001 width=70%}

12. Спуфинг - это подмена адреса отправителя в имейлах, вид фишинга.

![двенадцатое задание](image/12.png){#fig:001 width=70%}

13. Вирус-троян маскируется под легитимную программу, при этом содержа в себе вредоносное ПО.

![тринадцатое задание](image/13.png){#fig:001 width=70%}

14. В протоколе мессенджеров Signal ключ шифрования формируется при генерации первого сообщения стороной-отправителем.

![четырнадцатое задание](image/14.png){#fig:001 width=70%}

15. Суть сквозного шифрования состоит в том, что сообщения передаются по узлам связи (серверам) в зашифрованном виде.

![пятнадцатое задание](image/15.png){#fig:001 width=70%}

# Выводы

Я изучил основы защиты данных ПК/телефона.

# Список литературы

Конспекты к лекциям курса "Основы кибербезопасности".
