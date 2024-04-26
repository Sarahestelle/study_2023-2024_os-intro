---
## Front matter
title: "Четвертый этап индивидуального проекта"
subtitle: "Операционные системы"
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

- Продолжить редактирование своего сайта. Добавить ссылки на научные ресурсы.


# Задание

- Добавить к сайту ссылки на научные и библиометрические ресурсы.

1. Зарегистрироваться на соответствующих ресурсах и разместить на них ссылки на сайте:

- eLibrary : https://elibrary.ru/;
- Google Scholar : https://scholar.google.com/;
- ORCID : https://orcid.org/;
- Mendeley : https://www.mendeley.com/;
- ResearchGate : https://www.researchgate.net/;
- Academia.edu : https://www.academia.edu/;
- arXiv : https://arxiv.org/;
- github : https://github.com/.

2. Сделать пост по прошедшей неделе.

3. Добавить пост на тему по выбору:

- Оформление отчёта.
- Создание презентаций.
- Работа с библиографией.


# Выполнение лабораторной работы

- Зарегистрируемся на соответствующих ресурсах и разместим на них ссылки на сайте. (рис. [-@fig:001]).

![Рис.](image/1.jpg){#fig:001 width=70%}

- Результат на сайт. (рис. [-@fig:002]).

![Рис.](image/2.jpg){#fig:002 width=70%}

- Сделаем пост по прошедшей неделе.  (рис. [-@fig:003]).

![Рис.](image/3.jpg){#fig:003 width=70%}

- Результат на сайт. (рис. [-@fig:003]).

![Рис.](image/4.jpg){#fig:004 width=70%}

- Добавить пост на тему по выбору создания презентаций. (рис. [-@fig:005]).

![Рис.](image/5.jpg){#fig:005 width=70%}

- Результат на сайт. (рис. [-@fig:006]).

![Рис.](image/6.jpg){#fig:006 width=70%}

# Выводы

- В процессе выполнения этого этапа проекта я добавила на сайт ссылки на свои научные аккаунты, а также написала два  поста. 

# Список литературы{.unnumbered}

::: {#refs}
:::
