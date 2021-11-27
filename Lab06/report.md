---
# Front matter
lang: ru-RU
title: "Отчёт по лабораторной работе №6"
subtitle: "дисциплина: Информационная безопасность"
author: "Купатенко Владислав Георгиевич"

# Formatting
toc-title: ""
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

Развить навыки администрирования ОС Linux. Получить первое практическое знакомство с технологией SELinux. Проверить работу SELinx на практике совместно с веб-сервером Apache.

# Выполнение лабораторной работы

Проверил полтикиу Selinux, статус веб-сервера, его контекст безопасности (рис.1).

![Рисунок №1: Статусы](image/1.png){ #fig:001 width=70% }

Проверил состояние переключателей SELinux (рис.2).

![Рисунок №2: Переключатели](image/2.png){ #fig:002 width=70% }

Статистика по политике Selinux (рис.3).

![Рисунок №3: Статистика по политике Selinux](image/3.png){ #fig:003 width=70% }

Тип файлов и поддиректорий, круг пользователей в каталоге /var/www (рис. 4).

![Рисунок №4: /var/www](image/4.png){ #fig:003 width=70% }

Заполнен файл test.html (рис. 5).

![Рисунок №5: test.html ](image/5.png){ #fig:003 width=70% }

Контекст файла test.html (рис. 6).

![Рисунок №6: Контекст файла test.html](image/6.png){ #fig:003 width=70% }

Отображение файла на веб-странице (рис. 7).

![Рисунок №7: Отображение файла test.html](image/7.png){ #fig:003 width=70% }

Мануал для httpd_selinux отсутствует (рис. 8).

![Рисунок №8: man httpd_selinux](image/8.png){ #fig:003 width=70% }

Изменение контекста файла test.html (рис. 9).

![Рисунок №9: Новый контекст файла test.html](image/9.png){ #fig:003 width=70% }

Попытка открыть файл через браузер (рис. 10).

![Рисунок №10: Отсутствие доступа](image/10.png){ #fig:003 width=70% }

Права доступа и лог файл сервера (рис. 11).

![Рисунок №11: Лог файл messages](image/11.png){ #fig:003 width=70% }

Изменение порта с 80 на 81 в файле конфигурации (рис. 12).

![Рисунок №12: httpd.conf ](image/12.png){ #fig:003 width=70% }

Попытка открыть файл через браузер безуспешна, так как был изменен порт (рис. 13).

![Рисунок №13: Отсутсвие соединения](image/13.png){ #fig:003 width=70% }

Лог messages. (рис. 14).

![Рисунок №14: Лог messages.](image/14.png){ #fig:003 width=70% }

Определение порта 81 (рис. 15).

![Рисунок №15: Определение порта 81](image/15.png){ #fig:003 width=70% }

Возвращение контекста файлу test (рис. 16).

![Рисунок №16: Возвращение контекста файлу test](image/16.png){ #fig:003 width=70% }

Попытка открыть файл через браузер по порту 81 (рис. 17).

![Рисунок №17: Доступ по порту 81](image/17.png){ #fig:003 width=70% }

Файл конфигурации был изменен и приведен к порту 80. Удаление файла test.html (рис. 18).

![Рисунок №18: Удаление файла test.html](image/18.png){ #fig:003 width=70% }

# Выводы

Были развиты навыки администрирования ОС Linux. Получено первое практическое знакомство с технологией SELinux. Проверена работу SELinx на практике совместно с веб-сервером Apache.
