---
## Front matter
title: "Отчёт по второму этапу выполнения самостоятельного проекта"
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

* Научиться изменять информацию о себе на сайте.
* Научиться добавлять посты

# Задание

* поставить на сайт свою фотографию на сайт, добавить биографию, научные интересы и образование.
* Добавить посты о предыдущей неделе и управлении версиями.

# Выполнение второго этапа самостоятельного проекта

1. Добавил свою фотографию на сайт.(рис. 1)

<figure>![addPhoto](image/addPhoto.png "рис. 1")
	<img src="image/addPhoto.png" alt="рис. 1">
	<figcaption>рис. 1</figcaption>
<figure>

2. Добавил краткое описание себя.(рис. 2)

<figure>![addBio](image/addBio.png "рис. 2")
	<img src="image/addBio.png" alt="рис. 2">
	<figcaption>рис. 2</figcaption>
<figure>

3. Добавил информацию об интересах и образовании.(рис. 3)

<figure>![addInfo](image/addInfo.png "рис. 3")
	<img src="image/addInfo.png" alt="рис. 3">
	<figcaption>рис. 3</figcaption>
<figure>

4. Добавил пост о прошедшей неделе.(рис. 4)

<figure>![addBlog](image/addBlog.png "рис. 4")
	<img src="image/addBlog.png" alt="рис. 4">
	<figcaption>рис. 4</figcaption>
<figure>

5. Добавил пост об управлении версиями и git.(рис. 5)

<figure>![addGit](image/addGit.png "рис. 5")
	<img src="image/addGit.png" alt="рис. 5">
	<figcaption>рис. 5</figcaption>
<figure>

6. С помощью hugo создал сайт на локальном хосте.

# Выводы

* Я научился изменять информацию о себе и добавлять посты.
