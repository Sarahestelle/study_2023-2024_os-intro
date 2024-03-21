---
## Front matter
title: "Второй этап индивидуального проекта"
subtitle: " Создание сайт "
author: "Разанацуа Сара Естэлл"

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

- Продолжить работы со своим сайтом. Редактировать его в соответствие с требованиями. Добавить данные о себе на сайт. 


# Задание

- Разместить фотографию владельца сайта.
- Разместить краткое описание владельца сайта (Biography).
- Добавить информацию об интересах (Interests).
- Добавить информацию от образовании (Education).
- Сделать пост по прошедшей неделе.
- Добавить пост на тему по выбору: Управление версиями. Git. Непрерывная интеграция и непрерывное развертывание (CI/CD).

                                                                    
# Выполнение лабораторной работы

- сохраните фото в файл ~/work/blog/content/authors/admin (рис. [-@fig:001]).

![Запись фотографии](image/1.jpg){#fig:001 width=100%}

- Разместим краткое описание владельца сайта (Biography). Добавим информацию об интересах (Interests). Добавим информацию от образовании (Education). (рис. [-@fig:002]).

![Рис.](image/2.jpg){#fig:002 width=100%}

- Переходим на сайт с помощью команды  ~/bin/hugo server  (рис. [-@fig:003]).

![Рис.](image/3.jpg){#fig:003 width=100%}


(рис. [-@fig:004]).

![Результат на сайт](image/4.jpg){#fig:004 width=100%}

- Сделаем пост по прошедшей неделе. Добавим пост на тему по выбору: Управление версиями. Git. Непрерывная интеграция и непрерывное развертывание (CI/CD). (рис. [-@fig:005]).

![Рис.](image/5.jpg){#fig:005 width=100%}

(рис. [-@fig:006]).

![Результат на сайт](image/6.jpg){#fig:006 width=100%}


# Выводы

- В процесс выполнении второго этапа индивидуального проекта, я научилась редактировать данные о себе, а также писать посты и добавлять их на сайт.

# Список литературы{.unnumbered}

::: {#refs}
:::
