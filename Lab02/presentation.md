---
## Front matter
lang: ru-RU
title: "Отчёт по лабораторной работе №2"
author: |
	Купатенко Владислав Георгиевич\inst{1}
institute: |
	\inst{1}RUDN University, Moscow, Russian Federation

date: 1st of October, 2021, Moscow, Russia

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

# **Работа с атрибутами и правами доступа файлов и каталогов.**

# **1. Создание учетной записи**

Создана учетная запись гостя, задан пароль (рис.1).

![Рисунок №1: Характеристики виртуальной машины](image/1.png){ #fig:001 width=70% }

Проведена авторизация под новым пользователем, уточнены его имя и группа (рис.2).

![Рисунок №2: Авторизация](image/2.png){ #fig:002 width=70% }

Открыт и изучен файл /etc/passwd. Проведена фильрация по имени, определены существующие директории (рис.3).

![Рисунок №3: /etc/passwd](image/3.png){ #fig:003 width=70% }

# **2. Работа с правами**

Создана папка dir1, определены ее права. (рис. 4).

![Рисунок №4: Создание dir1](image/4.png){ #fig:003 width=70% }

Проведено снятие атрибутов с dir1 (рис. 5).

![Рисунок №5: Снятие атрибутов](image/5.png){ #fig:003 width=70% }

# **3. Заполнение таблиц**

Заполнена таблица 2.1 (рис. 6).

![Рисунок №6: Таблица 2.1](image/6.png){ #fig:003 width=70% }

Заполнена таблица 2.2 (рис. 7).

![Рисунок №7: Таблица 2.2](image/7.png){ #fig:003 width=70% }


# Выводы

Были приобретены практические навыки работы в консоли с атрибутами фай-
лов, закрепление теоретических основ дискреционного разграничения до-
ступа в современных системах с открытым кодом на базе ОС Linux.
