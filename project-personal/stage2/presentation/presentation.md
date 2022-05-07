---
## Front matter
lang: ru-RU
title: Индивидульный проект. 2 этап.
author: |
	Латыпова Диана. НФИбд-02-21
institute: |
	\inst{1}RUDN University, Moscow, Russian Federation

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

##  Цель работы

Добавление к сайту данные о себе.

## Выполнение индивидуального проекта

Для начала нужно установить фото профиля. (рис. [-@fig:001])

![Фото профиля](image/1%20avatar.png){ #fig:001 width=70% }

## Данные о себе

Далее переходим к заполнению данных о себе. Для этого открываем в Visual Studio Code файл _index.md(рис. [-@fig:002]). 

![Биография 1](image/2%20bio%201.png){ #fig:002 width=50% }

Внесла свои данные: ФИ, место учебы, краткую биографию,интересы, курс, социальные сети и немного о себе

## Пост по прошедшей неделе

После чего открыла терминал в каталоге ~/work/didi и с помощью команды(рис. [-@fig:003]): 

**hugo new --kind post post/My_last_week**

создала каталог My_last_week

![Команда hugo new](image/3%20my%20last%20week%201.png){ #fig:003 width=70% }

## Пост по прошедшей неделе

Также открыла в Visual Studio Code файл _index.md, только уже который находился в ~/work/didi/content/post/My_last_week и вставила, заготовленный мной, текст(рис. [-@fig:004]).

![Моя прошедшая неделя](image/4%20last%201.png){ #fig:004 width=70% }

## Пост "Управление верcиями. Git"

С помощью той же команды рядом с каталогом My_last_week создала каталог git(рис. [-@fig:005])

![Команда hugo new](image/5%20git.png){ #fig:005 width=60% }

Также открыв файл _index.md, находящийся в ~/work/didi/content/post/git, вставила, раннее заготовленный мной, текст

## Hugo

И наконец, нужно было перенести всю занесенную информацию выше на сайт. В ~/work/didi я открыла терминал и выполнила команды **hugo**  (рис. [-@fig:006])

![Hugo](image/7%20hugo.png){ #fig:006 width=70% }

## Обновление данных

После, перешла в каталог ~/work/didi/public, здесь открыла терминал, выполнила команды гит:

1  **git add .**

2  **git commit -am "2 этап"**

3  **git push**

Затем снова перешла в ~/work/didi и выполнила те же команды гит

## Сайт

Осталось лишь обновить сайт и посмотреть наши внесенные данные(рис. [-@fig:007])(рис. [-@fig:008])

![Checking (1)](image/10%20done%201.png){ #fig:007 width=50% }

![Checking (2)](image/10%20done%202.png){ #fig:008 width=50% }

## Вывод

Я добавила к сайту данные о себе, а именно: разместила фотографию владельца сайта, разместила краткое описание владельца сайта,добавила информацию об интересах, добавила информацию об образовании, сделала 2 поста по прошедшей неделе и "Управление версиями. Git".

