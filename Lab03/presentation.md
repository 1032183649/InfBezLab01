---
## Front matter
lang: ru-RU
title: "Отчёт по лабораторной работе №3"
author: |
	Купатенко Владислав Георгиевич\inst{1}
institute: |
	\inst{1}RUDN University, Moscow, Russian Federation

date: 12th of October, 2021, Moscow, Russia

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
---

# **Дискреционное разграничение прав в Linux. Два пользователя.**

# **1. Создание учетной записи**

Создана учетная запись гостя №2, задан пароль, пользователь добавлен в группу (рис.1).

![Рисунок №1: Создание записи](image/1.png){ #fig:001 width=70% }

Проведена проверка участия пользователя в группе гостей (рис.2).

![Рисунок №2: Проверка](image/2.png){ #fig:002 width=70% }

Открыт и изучен файл /etc/group (рис.3).

![Рисунок №3: /etc/group](image/3.png){ #fig:003 width=70% }

# **2. Работа с правами**

Изменены права для группы домашнего каталога пользователя и каталога dir1. Начаты опыты по доступу другого пользователя этой группы. (рис. 4).

![Рисунок №4: Опыты с доступом](image/4.png){ #fig:003 width=70% }

# **3. Заполнение таблиц**

Заполнена таблица 3.1 (рис. 5).

![Рисунок №5: Таблица 3.1](image/5.png){ #fig:003 width=70% }

Заполнена таблица 3.2 (рис. 6).

![Рисунок №6: Таблица 3.2](image/6.png){ #fig:003 width=70% }


# Выводы

Были приобретены практические навыки работы в консоли с атрибутами файлов для групп пользователей.
