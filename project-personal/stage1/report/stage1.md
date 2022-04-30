---
## Front matter
title: "Индивидуальный проект"
subtitle: "1 этап"
author: "Латыпова Диана. НФИбд-02-21"

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

Размещение на Github pages заготовки для персонального сайта.

# Задание

- Установить необходимое программное обеспечение.
- Скачать шаблон темы сайта.
- Разместить его на хостинге git.
- Установить параметр для URLs сайта.
- Разместить заготовку сайта на Github pages.

# Выполнение индивидуального проекта

До начала выполнения проекта я скачала Go (Golang) на Fedora 35. 

После чего, собственно, начала 1 этап  индивидуального проекта. Для реализации сайта использовали генератор статических сайтов Hugo. Скачала с сайта архив hugo_extended_0.98.0_Linux-64bit.tar.gz. После завершения установки разархивировала его. (рис. [-@fig:001])


![Скачивание архива](image/1%20download.png){ #fig:001 width=70% }

Открыв папку, вырезала, лежащий там, исполняемый файл hugo в, созданную в домашней папке, папку bin(рис. [-@fig:002]) 

![Перемещаем исполняемый файл hugo](image/2%20hugo%20peremestili.png){ #fig:002 width=70% }

В качестве шаблона индивидуального сайта использовали шаблон Hugo Academic Theme,перешли на сайт. Создала новый репозиторий в гите DLatypova(рис. [-@fig:003])

![Новый репозиторий](image/3%20sozdaniye%20repositoriya.png){ #fig:003 width=70% }

Скопировала ссылку (рис. [-@fig:004]) и склонировала репозиторий, создался каталог DLatypova с файлами(рис. [-@fig:005]).

![Копирование ссылки](image/4%20copy%20ccalku.png){ #fig:004 width=70% }

![Клонирование репозитория](image/5%20clone.png){ #fig:005 width=70% }

Затем выполнила hugo(рис. [-@fig:006]).

![hugo](image/6%20hugo.png){ #fig:006 width=70% }

Образовалась, пока ненужная нам, папка public. Удалим ее(рис. [-@fig:007]).

![Удаление public](image/7%20remove%20public.png){ #fig:007 width=70% }

Затем выполнила hugo server, после чего должна была появиться ссылка на наш сайт, но, скопировав ссылку на сайт и вставив в браузер, нам выдало ошибку(рис. [-@fig:008])

![hugo server, ошибка](image/8%20hugo%20server%20and%20oshibka.png){ #fig:008 width=70% }

После чего я выполнила все вышеописанные пункты заново, создала новый репозиторий didi. Однако, сайт все равно не открывался. Только после настройки прав доступа и перезапуска консоли сайт открылся(рис. [-@fig:009])

![Новый репозиторий didi, рабочий сайт](image/9%20sayt%20zarabotal.png){ #fig:009 width=70% }

Чтобы убрать зеленый фон на сайте, мы удалили файл demo.md(рис. [-@fig:010])

![Новый репозиторий didi, рабочий сайт](image/10%20remove%20demo.png){ #fig:010 width=70% }

Далее мы создали еще один новый репозиторий dlatypova.github.io (рис. [-@fig:011])

![Новый репозиторий dlatypova.github.io](image/6.1%20new%20rep.png){ #fig:011 width=70% }

Находясь в каталоге work, клонируем рядом с нашим репозиторием didi новый репозиторий dlatypova.github.io и создаем ветку main с помощью 

**get checkout -b main** (рис. [-@fig:012])

![Клонирование dlatypova.github.io, создание новой ветки](image/11%20new%20vetka.png){ #fig:012 width=70% }

Далее создали файл README.md и добавили в гит.(рис. [-@fig:013])(рис. [-@fig:014])

![Создание и добавление в  гит файла 1](image/12%20dobavlenie%20readme%201.png){ #fig:013 width=70% }

![Создание и добавление в  гит файла 2](image/12%20dobavlenie%20readme%202.png){ #fig:014 width=70% }

Чтобы убедиться, что далее все окажется в ветке main выполним команду 

**git push origin main**(рис. [-@fig:015])

![Создание и добавление в  гит файла 2](image/13%20perestrahovka.png){ #fig:015 width=70% }

Далее используем команду 

**git submodule add -b main < ссылка SSH >**(рис. [-@fig:016])

![Команда git submodule add -b main < ссылка SSH >](image/15%20submodule.png){ #fig:016 width=70% }

Комментируем public(рис. [-@fig:017]).

![#public](image/16%20comment%20public.png){ #fig:017 width=70% }

Снова выполняем команду выше, после чего public добавится в индекс(рис. [-@fig:018])

![Добавление public в индекс](image/17%20dobavlenie%20v%20index.png){ #fig:018 width=70% }

Далее в гит добавляем папки(рис. [-@fig:019])(рис. [-@fig:020])

![Добавление папок в гит 1](image/18%20dobavlenie%20papok.png){ #fig:019 width=70% }

![Добавление папок в гит 2](image/18%20dobavlenie%20papok.png){ #fig:020 width=70% }

Снова используем команду  

**git push origin main**(рис. [-@fig:021])

![Команда git push origin main](image/19%20git%20push.png){ #fig:021 width=70% }

Обновляя сайт гит, видим, что, нужные нам, папки добавились в репозиторий.

И наконец, копируем URLs нашего сайта и вставляем в браузер, ждем несколько секунд, после обновления, собственно, видим страницу нашего сайта(рис. [-@fig:022])(рис. [-@fig:023]).

![Сайт 1](image/20%20cayt.png){ #fig:022 width=70% }

![Сайт 2](image/20%20done.png){ #fig:023 width=70% }

У меня все получилось.

***На этом завершается 1 этап индивидуального проекта.***

# Вывод

Я разместила на Github pages заготовки для персонального сайта.
