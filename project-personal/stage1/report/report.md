---
## Front matter
title: "Индивидуальный проект. Первый этап"
subtitle: "Установка Kali Linux на виртуальную машину"
author: "Чемоданова Ангелина Александровна"

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
lot: false # List of tables
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
## Pandoc-crossref LaTeX customization
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

Установить дистрибутивa Kali на виртуальную машину.

# Выполнение лабораторной работы

1. С официального сайта Kali Linux качаем нужный нам дистрибутив. В моем случае я установила архив формата 7z. (рис. [-@fig:001]).

![Распаковка архива 7z Kali Linux](image/1.png){#fig:001 width=70%}

2.  Распаковав его я получила два файла форматов vdi и vbox. (рис. [-@fig:002]).

![Распакованные файлы](image/2.png){#fig:002 width=70%}

3.  Затем в VirtualBox я нажала на кнопку "добавить" и выбрала там скачанный файл формата vbox. После этого у меня появилась новая виртуальная машина.  (рис. [-@fig:003]).

![Установленная виртуальная машина](image/3.png){#fig:003 width=70%}

4. Изменяем имя машины.   (рис. [-@fig:004]).

![Имя установленной виртуальной машины](image/4.png){#fig:004 width=70%}

5. Количество памяти, основные характеристики материнской платы.   (рис. [-@fig:005]).

![Основные характеристики материнской платы](image/5.png){#fig:005 width=70%}

6. Количество процессоров и предел загрузки ЦПУ. (рис. [-@fig:006]).

![Количество процессоров и предел загрузки ЦПУ](image/6.png){#fig:006 width=70%}

7. Проверка установленного образа. (рис. [-@fig:007]).

![Проверка установленного образа](image/7.png){#fig:007 width=70%}

8. Запуск Kali Linux и ввод пароля. (рис. [-@fig:008]).

![Запуск Kali Linux и ввод пароля](image/8.png){#fig:008 width=70%}

9. Запущенная машина с дистрибутивом Kali Linux.  (рис. [-@fig:009]).

![Запущенная машина с дистрибутивом Kali Linux](image/9.png){#fig:009 width=70%}


# Выводы

В результате выполнения работы мы приобрели практические навыки установки операционной системы на виртуальную машину, поставили Kali Linux на свою виртальную машину. 



