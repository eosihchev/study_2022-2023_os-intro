---
## Front matter
title: "Отчёт. Инвидуальный проект. Этап №1."
subtitle: "дисциплина: Операционные системы"
author: "Сычев Егор Олегович"

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
## Pandoc-crossref LaTeX customization5
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

Разместить на Github pages заготовку для персонального сайта.


# Выполнение первого этапа индивидуального проекта

1. Установка необходимого программного обеспечения.

![sudo dnf install go hugo](image/1.png)

2. Создание репозитория на основае шаблона и настройка каталога.

![Репозиторий github](image/2.png)

![Клонирование](image/3.png)

3. Команда hugo server и открытие сайта.

![hugo server](image/4.png)

![ссылка localhost](image/5.png)

4. Удаление первого блока на сайте.

![Удаление ненужной части сайта](image/6.png)

5. Создание нового репозитория для развертывания на базе страниц github.

![Репозиторий github](image/7.png)

6. Клонирование и настройка каталога.

![Клонирование](image/8.png)

![git checkout](image/9.png)

7. Закомментирование public. 

![Комментирование](image/10.png)

8. Добавление существующего репозитория в индекс.

![git submodule](image/11.png)

9. Команды для развертывания сайта.

![hugo](image/12.png)

![git add, git commit, git push](image/13.png)

![git add, git commit, git push](image/14.png)

![Сайт](image/15.png)


# Вывод

Я разместил на Github pages заготовку для персонального сайта.
