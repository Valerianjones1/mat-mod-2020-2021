---
# Front matter
lang: ru-RU
title: "Отсчет по лабораторной работе №1"
subtitle: "Работа с GIT и Markdown"
author: "Динькиев Валерий"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=MiKTeX
romanfontoptions: Ligatures=MiKTeX
sansfontoptions: Ligatures=MiKTeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: xelatex
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

Познакомиться с GIT и языком разметки Markdown.

# Задание

- Создать репозиторий на GitHub
- Выгрузить файлы на GitHub
- Сгенерировать ключ SSH
- Сделать свой первый релиз на GitHub


# Выполнение лабораторной работы

1. Установил имя и электронную почту

2. Установил параметры окончаний строк (рис. -@fig:001)
3. Установил отображения unicode (рис. -@fig:001)

![Установка параметров окончаний строк и отображения unicode](image/0.png){ #fig:001 width=90% }

4. Создал репозиторий из своего каталога (рис. -@fig:002)

5. Добавил файл README.md в репозиторий (рис. -@fig:002)

![Создание репозитория из каталога](image/1.png){ #fig:002 width=90% }

6. Создал репозиторий на GitHub и выгрузил содержимое каталога с помощью git push (рис. -@fig:003)

![Репозиторий на GitHub](image/2.png){ #fig:003 width=90% }

7. Сгенерировал ключ SSH и настроил его в GitHub (рис. -@fig:004)

![ключ SSH на GitHub](image/3.png){ #fig:004 width=90% }

8. С помощью команды git clone выгрузил шаблоны презентации и отсчета (рис. -@fig:005)

![Шаблоны презентации и отсчета](image/4.png){ #fig:005 width=90% }

9. Сделал первый релиз на GitHub (рис. -@fig:006)

![Мой первый релиз на GitHub](image/5.png){ #fig:006 width=90% }

10. Проверил соединение SSH (рис. -@fig:007)

![Проверка соединения SSH](image/6.png){ #fig:007 width=90% }


# Выводы

Познакомился с GIT и языком разметки Markdown.