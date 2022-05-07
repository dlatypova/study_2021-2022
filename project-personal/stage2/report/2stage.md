---
## Front matter
title: "Индивидуальный проект"
subtitle: "2 этап"
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

Добавление к сайту данные о себе

# Задание

Список добавляемых данных.
- Разместить фотографию владельца сайта.
- Разместить краткое описание владельца сайта (Biography)
- Добавить информацию об интересах (Interests).
- Добавить информацию об образовании (Education).

Сделать пост по прошедшей неделе.

Добавить пост на тему по выбору:
- Управление версиями. Git.
- Непрерывная интеграция и непрерывное развертывание (CI/CD).

# Выполнение индивидуального проекта

Для начала нужно установить фото профиля, поэтому я перенесла свою фотографию из Загрузки в, нужный нам, каталог ~/work/didi/content/authors/admin. (рис. [-@fig:001])

![Фото профиля](image/1%20avatar.png){ #fig:001 width=70% }

Далее переходим к заполнению данных о себе. Для этого открываем в Visual Studio Code файл _index.md, который находится в том же каталоге, что и фото профиля, ~/work/didi/content/authors/admin(рис. [-@fig:002]). 

![Биография 1](image/2%20bio%201.png){ #fig:002 width=70% }

Внесла свои данные: ФИ, место учебы, краткую биографию,интересы, курс, социальные сети и немного о себе(рис. [-@fig:003])(рис. [-@fig:004])(рис. [-@fig:005]).

![Биография 2](image/2%20bio%202.png){ #fig:003 width=70% }

![Биография 3](image/2%20bio%203.png){ #fig:004 width=70% }

![Биография 4](image/2%20bio%204.png){ #fig:005 width=70% }

После чего открыла терминал в каталоге ~/work/didi и с помощью команды(рис. [-@fig:006]): 

**hugo new --kind post post/My_last_week**

создала каталог My_last_week(рис. [-@fig:007]).

![Команда hugo new](image/3%20my%20last%20week%201.png){ #fig:006 width=70% }

![My_last_week](image/3%20last%20week%202.png){ #fig:007 width=70% }

Также открыла в Visual Studio Code файл _index.md, только уже который находился в ~/work/didi/content/post/My_last_week и вставила, заготовленный мной, текст(рис. [-@fig:008])(рис. [-@fig:009]).

![Моя прошедшая неделя (1)](image/4%20last%201.png){ #fig:008 width=70% }

![Моя прошедшая неделя (2)](image/4%20last%202.png){ #fig:009 width=70% }

С помощью той же команды рядом с каталогом My_last_week создала каталог git(рис. [-@fig:010])

![Команда hugo new](image/5%20git.png){ #fig:010 width=70% }

Также открыв файл _index.md, находящийся в ~/work/didi/content/post/git, вставила, раннее заготовленный мной, текст(рис. [-@fig:011])(рис. [-@fig:012])

![Управление версиями. Git (1)](image/6%20git%201.png){ #fig:011 width=70% }

![Управление версиями. Git (2)](image/6%20git%202.png){ #fig:012 width=70% }

И наконец, нужно было перенести всю занесенную информацию выше на сайт. В ~/work/didi я открыла терминал и выполнила команды **hugo**  (рис. [-@fig:013])

![Hugo](image/7%20hugo.png){ #fig:013 width=70% }

После, перешла в каталог ~/work/didi/public, здесь открыла терминал, выполнила команды гит(рис. [-@fig:014]):

1  **git add .**

2  **git commit -am "2 этап"**

3  **git push**

![Команды гит (public)](image/8%20public.png){ #fig:014 width=70% }

Затем снова перешла в ~/work/didi и выполнила те же команды гит(рис. [-@fig:015]):

![Команды гит (didi)](image/9%20didi.png){ #fig:015 width=70% }

Осталось лишь обновить сайт и посмотреть наши внесенные данные(рис. [-@fig:016])(рис. [-@fig:017])

![Checking (1)](image/10%20done%201.png){ #fig:016 width=70% }

![Checking (2)](image/10%20done%202.png){ #fig:017 width=70% }

# Выводы

Я добавила к сайту данные о себе, а именно: разместила фотографию владельца сайта, разместила краткое описание владельца сайта,добавила информацию об интересах, добавила информацию об образовании, сделала 2 поста по прошедшей неделе и "Управление версиями. Git".
