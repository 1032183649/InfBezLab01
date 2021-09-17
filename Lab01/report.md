---
# Front matter
lang: ru-RU
title: "Отчёт по лабораторной работе №1"
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

Приобретение практических навыков установки операционной систе-
мы на виртуальную машину, настройки минимально необходимых для
дальнейшей работы сервисов.

# Задание

Установка и конфигурация операционной системы на виртуальную машину.

# Выполнение лабораторной работы

Собрана виртуальная машина со следующими характеристиками (рис.1) на базе операционной системы CentOS 8.

![Рисунок №1: Характеристики виртуальной машины](image/1.png){ #fig:001 width=70% }

Проведена установка операционной системы на виртуальную машину (рис.2, 3).

![Рисунок №2: Базовые настройки операционной системы при установке](image/2.png){ #fig:002 width=70% }

![Рисунок №3: Процесс установки операционной системы](image/3.png){ #fig:003 width=70% }

После установки выполнен вход в запись администратора (рис. 4).

![Рисунок №4: Вход под root-правами](image/4.png){ #fig:003 width=70% }

Проведены обновление системы и установка некоторых программ (рис. 5, 6).

![Рисунок №5: Обновление системы](image/5.png){ #fig:003 width=70% }

![Рисунок №6: Установка программы](image/6.png){ #fig:003 width=70% }

Изменены свойства жесткого диска, открыт множественный доступ (рис. 7).

![Рисунок №7: Свойства носителя](image/7.png){ #fig:003 width=70% }

C целью соблюдения соглашения о наименовании были внесены следующие изменения (рис. 8, 9).

![Рисунок №8: Изменено название системы](image/8.png){ #fig:003 width=70% }

![Рисунок №9: Изменено название виртуальной машины](image/9.png){ #fig:003 width=70% }

# Выводы

Были приобретены практические навыки установки операционной систе-
мы на виртуальную машину, настройки минимально необходимых для
дальнейшей работы сервисов.
