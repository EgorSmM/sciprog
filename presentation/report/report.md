---
## Front matter
title: "Доклад"
subtitle: "Научные статистические расчеты. Программное обеспечение для реализации статистических расчётов."
author: 
  - Смирнов-Мальцев Е. Д.

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

- Выделить задачи научной статистики,
- Выполнить подсчет основных статистических метрик.

# Задачи

# Теоретическое введение

Статистика --- совокупность числовых показателей, характеризующих те или иные явления и процессы. Статистика имеет дело, прежде
всего с количественной стороной явлений и процессов.
Статистические данные языком цифр характеризуют размеры и
количественные соотношения (объемы, структуру, темпы развития и т.п.)
явлений и проявляющиеся в них закономерности.

Важнейшими элементами статистической методологии являются:
массовое наблюдение, группировки, применение обобщающих (сводных)
характеристик. Статистическое исследование
включает в себя:
- разработку программы статистического наблюдения (определение
объекта, единицы и формы наблюдения, разработку методик расчета
запрашиваемых показателей и предполагаемые результаты
обработки полученных данных);
- сбор массовых данных о статистической совокупности
(непосредственно статистическое наблюдение);
- обработку данных (сводку, группировку);
- анализ полученной информации.



# Заключение

Для исследования модели Хищник-жертва в нашей работе будут использованы метод Эйлера и методы Рунге-Кутта, а программная реализация будет выполнена в системе математических вычисленый Octave.

# Список литературы{.unnumbered}

::: {#refs}
:::
