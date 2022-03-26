---
# Front matter
title: "Отчет по лабораторной работе 5"
subtitle: "Модель хищник-жертва"
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
mainfont: PTSerif-Regular.ttf
romanfont: PTSerif-Regular.ttf
sansfont: PTSerif-Regular.ttf
monofont: PTSerif-Regular.ttf
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

Построить модель взаимодействия двух видов типа «хищник — жертва» -
модель Лотки-Вольтерры.

# Задание

Постройте график зависимости численности хищников от численности жертв,
а также графики изменения численности хищников и численности жертв при
следующих начальных условиях: х0=7, у0=9 . 

# Теоретическое введение

Данная двувидовая модель основывается на
следующих предположениях:
1. Численность популяции жертв x и хищников y зависят только от времени
(модель не учитывает пространственное распределение популяции на
занимаемой территории)
2. В отсутствии взаимодействия численность видов изменяется по модели
Мальтуса, при этом число жертв увеличивается, а число хищников падает
3. Естественная смертность жертвы и естественная рождаемость хищника
считаются несущественными
4. Эффект насыщения численности обеих популяций не учитывается
5. Скорость роста численности жертв уменьшается пропорционально
численности хищников

# Выполнение лабораторной работы

Ввел коэффиценты (рис. [-@fig:001])

![Коэффиценты](image/1.jpg){ #fig:001 width=70% }

Ввел дифференциальное уравнение (рис. [-@fig:002])

![Уравнение](image/2.jpg){ #fig:002 width=70% }

Построил графики (рис. [-@fig:003])

![Подгон результатов и отрисовка графиков](image/3.jpg){ #fig:003 width=70% }

График зависимости численности хищников от численности жертв (рис. [-@fig:004])

![График 1](image/4.jpg){ #fig:004 width=70% }

График изменения численности хищников (рис. [-@fig:005])

![График 2](image/5.jpg){ #fig:005 width=70% }

График изменения численности хищников жертв(рис. [-@fig:006])

![График 3](image/6.jpg){ #fig:006 width=70% }


# Выводы

Я построил график зависимости численности хищников от численности жертв.

# Список литературы{.unnumbered}

::: {#refs}
:::
