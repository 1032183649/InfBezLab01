---
# Front matter
lang: ru-RU
title: "Отчёт по лабораторной работе №3"
subtitle: "дисциплина: Информационная безопасность"
author: "Купатенко Владислав Георгиевич"

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
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
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

Получение практических навыков работы в консоли с атрибутами файлов для групп пользователей.

# Выполнение лабораторной работы

Создана учетная запись гостя №2, задан пароль, пользователь добавлен в группу (рис.1).

![Рисунок №1: Создание записи](image/1.png){ #fig:001 width=70% }

Проведена проверка участия пользователя в группе гостей (рис.2).

![Рисунок №2: Проверка](image/2.png){ #fig:002 width=70% }

Открыт и изучен файл /etc/group (рис.3).

![Рисунок №3: /etc/group](image/3.png){ #fig:003 width=70% }

Изменены права для группы домашнего каталога пользователя и каталога dir1. Начаты опыты по доступу другого пользователя этой группы. (рис. 4).

![Рисунок №4: Опыты с доступом](image/4.png){ #fig:003 width=70% }

Заполнена таблица 3.1 (рис. 5).

![Рисунок №5: Таблица 3.1](image/5.png){ #fig:003 width=70% }

Заполнена таблица 2.2 (рис. 7).

![Рисунок №6: Таблица 3.2](image/6.png){ #fig:003 width=70% }

# Выводы

Были приобретены практические навыки работы в консоли с атрибутами файлов для групп пользователей.
