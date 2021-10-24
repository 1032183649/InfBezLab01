---
## Front matter
lang: ru-RU
title: "Отчёт по лабораторной работе №4"
author: |
	Купатенко Владислав Георгиевич\inst{1}
institute: |
	\inst{1}RUDN University, Moscow, Russian Federation

date: 24th of October, 2021, Moscow, Russia

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

# **Дискреционное разграничение прав в Linux. Расширенные атрибуты.**

# **1. Взаимодействие от пользователя guest**

Определены расширенные атрибуты файла, установлены новые права и проведена попытка установить атрибут от пользователя guest (рис.1).

![Рисунок №1: Атрибуты файла](image/1.png){ #fig:001 width=70% }

# **2. Установка атрибута а**

Установлен атрибут а от имени суперпользователя (рис.2).

![Рисунок №2: Установка атрибута а](image/2.png){ #fig:002 width=70% }

Попытки взаимодействия с файлом после установки атрибута а (рис.3, 4).

![Рисунок №3: Взаимодействие с файлом после установки атрибута а](image/3.png){ #fig:003 width=70% }

![Рисунок №4](image/4.png){ #fig:003 width=70% }

# **3. Установка атрибута i**

Установка нового атрибута i от имени суперпользователя (рис. 5).

![Рисунок №5: Новый атрибут i](image/5.png){ #fig:003 width=70% }

Попытка взаимодействия с файлом после установки атрибута i (рис. 7).

![Рисунок №6: Взаимодействие с файлом после установки атрибута i](image/6.png){ #fig:003 width=70% }

# Выводы

Были приобретены практические навыкиработы в консоли с расширенными атрибутами файлов.
