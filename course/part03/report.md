---
## Front matter
title: "Внешний курс раздел 3"
subtitle: "Криптография на практике"
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

Изучить основы криптографии.

# Выполнение работы

1. В асимметричных криптографических примитивах обе стороны имеют пару ключей - публичный и секретный.

![первое задание](image/1.png){#fig:001 width=70%}

2. Криптографическая хэш-функция, в отличие от обычной хэш-функции, не обеспечивает конфиденциальность захэшированных данных, но она стойкая к коллизиям, эффективно вычисляется, дает на выходе фиксированное число бит независимо от объема входных данных.

![второе задание](image/2.png){#fig:001 width=70%}

3. К алгоритмам цифровой подписи относятся зарубежные RSA и ECDSA, российский ГОСТ Р 34.10-2012.

![третье задание](image/3.png){#fig:001 width=70%}

4.  Код аутентификации сообщения относится к симметричным примитивам.

![четвертое задание](image/4.png){#fig:001 width=70%}

5. Обмен ключами Диффи-Хэллмана - это асимметричный примитив генерации общего секретного ключа.

![пятое задание](image/5.png){#fig:001 width=70%}

6. Протокол электронной цифровой подписи относится к протоколам с публичным ключом.

![шестое задание](image/6.png){#fig:001 width=70%}

7. Алгоритм верификации электронной цифровой подписи требует на вход подпись, открытый ключ, сообщение.

![седьмое задание](image/7.png){#fig:001 width=70%}

8. Электронная цифровая подпись не обеспечивает конфиденциальность.

![восьмое задание](image/8.png){#fig:001 width=70%}

9. Для отправки налоговой отчетности в ФНС понадобится самый сильный тип сертификата электронной подписи - усиленная квалификационная.

![девятое задание](image/9.png){#fig:001 width=70%}

10. Квалифицированный сертификат ключа проверки электронной подписи можно получить в удостоверяющем (сертификационном) центре.

![десятое задание](image/10.png){#fig:001 width=70%}

11. MasterCard и МИР являются платежными системами в предоставленном в задании списке.

![одиннадцатое задание](image/11.png){#fig:001 width=70%}

12. Примерами многофакторной аутентификации являются комбинация проверка пароля + код в sms сообщении, комбинация код в sms сообщении + отпечаток пальца, капча с паролем и пароль с пин кодом не являются примерами многофакторной аутентификации.

![двенадцатое задание](image/12.png){#fig:001 width=70%}

13. При онлайн платежах сегодня используется многофакторная аутентификация покупателя перед банком-эмитентом - банком, на счете которого покупатель хранит денежные средства.

![тринадцатое задание](image/13.png){#fig:001 width=70%}

14. Сложность нахождения прообраза как свойство криптографической хэш-функции используется в доказательстве работы майнера.

![четырнадцатое задание](image/14.png){#fig:001 width=70%}

15. Консенсус в некоторых системах блокчейн обладает свойствами: открытость, живучесть, постоянство.

![пятнадцатое задание](image/15.png){#fig:001 width=70%}

16. Цифровая подпись используется в качестве криптографического примитива в блокчейне.

![шестнадцатое задание](image/16.png){#fig:001 width=70%}

# Выводы

Я изучил основы криптографии.

# Список литературы

Конспекты к лекциям курса "Основы кибербезопасности".
