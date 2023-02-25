---
## Front matter
title: "Отчёт по лабораторной работе №3"
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

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown


# Выполнение лабораторной работы

1. Создание заголовка.

![Заголовок](image/1.png)

2. Внутри каждого блока пишем то, что нам нужно.

![Текст](image/2.png)

3. Создаем нумерованный список.

![Список](image/3.png)

4. Для картинок: указываем путь и подписываем их.

![Картинка](image/4.png)

5. После сохраняем md файл и прописываем команду make.

![Компиляция](image/5.png)

6. Получаем ещё 2 файла pdf и docx.

![Каталог с файлами](image/6.png)

![pdf](image/7.png)

![docx](image/8.png)


# Вывод

Я научился оформлять отчёты с помощью легковесного языка разметки Markdown
