---
# Front matter
title: "Отчет по лабораторной работе 4"
subtitle: "Модель гармонических колебаний"
author: "Илья Валерьевич Фирстов"

# Generic otions
lang: ru-RU
toc-title: "Содержание"

# Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

# Pdf output format
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
### Fonts
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
## Misc options
indent: true
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Решить уравнение гармонического осциллятора и построить фазовый портрет в среде scilab

# Задание

Решить уравнение гармонического осциллятора и построить фазовый портрет для данных случаев:

![Задание](image/8.jpg){ #fig:008 width=70% }

# Теоретическое введение

Движение грузика на пружинке, маятника, заряда в электрическом контуре, а
также эволюция во времени многих систем в физике, химии, биологии и других
науках при определенных предположениях можно описать одним и тем же
дифференциальным уравнением, которое в теории колебаний выступает в качестве
основной модели. Эта модель называется линейным гармоническим осциллятором.

# Выполнение лабораторной работы

Ввел начальные условия для 1 случая (рис. [-@fig:001])

![Начальные условия](image/1.jpg){ #fig:001 width=70% }

Ввел левую и правую часть уравнения для 1 случая (рис. [-@fig:002])

![Уравнение](image/2.jpg){ #fig:002 width=70% }

Ввел начальную точку для 1 случая (рис. [-@fig:003])

![Начальная точка](image/3.jpg){ #fig:003 width=70% }

Решил уравнение и построил график для 1 случая (рис. [-@fig:004])

![Решение уравнения](image/4.jpg){ #fig:004 width=70% }

Фазовый портрет для 1 случая (рис. [-@fig:005])

![Фазовый портрет 1](image/5.jpg){ #fig:005 width=70% }

Затем для 2 случая переопределил начальные условия, после чего снова решил уравнение и построил график(рис. [-@fig:006])

![Изменения общего вида для 2 случая](image/6.jpg){ #fig:006 width=70% }

Фазовый портрет для 2 случая (рис. [-@fig:009])

![Фазовый портрет 2](image/9.jpg){ #fig:009 width=70% }

Затем для 3 случая переопределил начальные условия, после чего снова решил уравнение и построил график(рис. [-@fig:007])

![Изменения общего вида для 3 случая](image/7.jpg){ #fig:007 width=70% }

Фазовый портрет для 3 случая (рис. [-@fig:010])

![Фазовый портрет 3](image/10.jpg){ #fig:010 width=70% }

# Выводы

Я ознакомился с решением уравнений гармонического осциллятора и построил фазовый портрет.

# Список литературы{.unnumbered}

::: {#refs}
:::
