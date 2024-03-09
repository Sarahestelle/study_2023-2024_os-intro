---
## Front matter
title: "Лабораторная работа №4"
subtitle: "Лабораторная работа Продвинутое использование git."
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

- Получение навыков правильной работы с репозиториями git.

# Задание

- Выполнить работу для тестового репозитория.
- Преобразовать рабочий репозиторий в репозиторий с git-flow и conventional commits.

# Выполнение лабораторной работы

## Установка программного обеспечения

- Установка git-flow. (рис. [-@fig:001]).

![Рисунок 1](image/1.jpg){#fig:001 width=100%}

(рис. [-@fig:002]).

![Рисунок 2](image/2.jpg){#fig:002 width=100%}

## Установка Node.js
- На Node.js базируется программное обеспечение для семантического версионирования и общепринятых коммитов. (рис. [-@fig:003]).

![Рисунок 3](image/3.jpg){#fig:003 width=100%}

## Настройка Node.js

- Для работы с Node.js добавим каталог с исполняемыми файлами, устанавливаемыми yarn, в переменную PATH. (рис. [-@fig:004]).

![Рисунок 4](image/4.jpg){#fig:004 width=100%}

## Общепринятые коммиты

- Данная программа используется для помощи в форматировании коммитов. рис. [-@fig:006]).

![Рисунок 5](image/6.jpg){#fig:006 width=100%}

- Данная программа используется для помощи в создании логов.  рис. [-@fig:005]).

![Рисунок 6](image/5.jpg){#fig:005 width=100%}

## Практический сценарий использования git

- Создайте репозиторий на GitHub. Для примера назовём его git-extended. рис. [-@fig:008]).

![Рисунок 7](image/8.jpg){#fig:008 width=100%}

- Конфигурация для пакетов Node.js. рис. [-@fig:009]).

![Рисунок 8](image/9.jpg){#fig:009 width=100%}

- Название пакета.Сконфигурим формат коммитов. рис. [-@fig:010]).

![Рисунок 9](image/10.jpg){#fig:010 width=100%}

- Конфигурация git-flow. рис. [-@fig:011]).

![Рисунок 10](image/11.jpg){#fig:011 width=100%}

# Выводы

- Я изучала как получить навыки правильной работы с репозиториями git.


# Список литературы{.unnumbered}

::: {#refs}
:::
