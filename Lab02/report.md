---
# Front matter
lang: ru-RU
title: "Отчёт по лабораторной работе №2"
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

Получение практических навыков работы в консоли с атрибутами фай-
лов, закрепление теоретических основ дискреционного разграничения до-
ступа в современных системах с открытым кодом на базе ОС Linux.

# Выполнение лабораторной работы

Создана учетная запись гостя, задан пароль (рис.1).

![Рисунок №1: Создание записи](image/1.png){ #fig:001 width=70% }

Проведена авторизация под новым пользователем, уточнены его имя и группа (рис.2).

![Рисунок №2: Авторизация](image/2.png){ #fig:002 width=70% }

Открыт и изучен файл /etc/passwd. Проведена фильрация по имени, определены существующие директории (рис.3).

![Рисунок №3: /etc/passwd](image/3.png){ #fig:003 width=70% }

Создана папка dir1, определены ее права. (рис. 4).

![Рисунок №4: Создание dir1](image/4.png){ #fig:003 width=70% }

Проведено снятие атрибутов с dir1 (рис. 5).

![Рисунок №5: Снятие атрибутов](image/5.png){ #fig:003 width=70% }

Заполнена таблица 2.1 (рис. 6).

![Рисунок №6: Таблица 2.1](image/6.png){ #fig:003 width=70% }

Заполнена таблица 2.2 (рис. 7).

![Рисунок №7: Таблица 2.2](image/7.png){ #fig:003 width=70% }

# Выводы

Были приобретены практические навыки работы в консоли с атрибутами фай-
лов, закрепление теоретических основ дискреционного разграничения до-
ступа в современных системах с открытым кодом на базе ОС Linux.
