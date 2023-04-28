---
## Front matter
title: "Отчёт по третьему этапу выполнения самостоятельного проекта"
subtitle: ""
author: "Смирнов-Мальцев Егор Дмитриевич"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc-depth: 2
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
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

* Научиться добавлять информацию о навыках опыте и достижениях.

# Задание

* поставить на сайт свою фотографию на сайт, добавить биографию, научные интересы и образование.
* Добавить посты о предыдущей неделе и управлении версиями.

# Задание:

1. Добавить к сайту достижения.
* Добавить информацию о навыках (Skills).
* Добавить информацию об опыте (Experience).
* Добавить информацию о достижениях (Accomplishments).

2. Сделать пост по прошедшей неделе.

3. Добавить пост на тему по выбору:
* Легковесные языки разметки.
* Языки разметки. LaTeX.
* Язык разметки Markdown.

# Выполнение третьего этапа самостоятельного проекта

1. Добавил информацию о своих навыках на сайт (рис. 1).

<figure>![skills](image/skills.png "рис. 1")
	<img src="image/skills.png" alt="рис. 1">
	<figcaption>рис. 1</figcaption>
<figure>

2. Добавил информацию о своем опыте (рис. 2).

<figure>![exp](image/exp.png "рис. 2")
	<img src="image/exp.png" alt="рис. 2">
	<figcaption>рис. 2</figcaption>
<figure>

3. Добавил информацию о своих достижениях (рис. 3).

<figure>![accomp](image/accomp.png "рис. 3")
	<img src="image/accomp.png" alt="рис. 3">
	<figcaption>рис. 3</figcaption>
<figure>

4. Добавил пост о прошедшей неделе.(рис. 4)

<figure>![addBlog](image/addBlog.png "рис. 4")
	<img src="image/addBlog.png" alt="рис. 4">
	<figcaption>рис. 4</figcaption>
<figure>

5. Добавил пост о языках разметки (рис. 5).

<figure>![html](image/html.png "рис. 5")
	<img src="image/html.png" alt="рис. 5">
	<figcaption>рис. 5</figcaption>
<figure>

# Выводы

* Я научился добавлять информацию о своих успехах.
