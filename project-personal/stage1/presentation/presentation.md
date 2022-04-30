---
## Front matter
lang: ru-RU
title: Индивидуальный проект. 1 этап
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

## Цель работы

Размещение на Github pages заготовки для персонального сайта.

## Задание

- Установить необходимое программное обеспечение.
- Скачать шаблон темы сайта.
- Разместить его на хостинге git.
- Установить параметр для URLs сайта.
- Разместить заготовку сайта на Github pages.

## Подготовка к выполнению индивидуального проекта

До начала выполнения проекта я скачала Go (Golang) на Fedora 35. 
Команды:

**sudo dnf -y update**

**sudo dnf -y install go**

**$ go version**
**go version go1.16.8 linux/amd64**

## Выполнение индивидуального проекта

Для реализации сайта использовали генератор статических сайтов Hugo. Скачала с сайта архив hugo_extended_0.98.0_Linux-64bit.tar.gz. После завершения установки разархивировала его. (рис. [-@fig:001])

![Скачивание архива](image/1%20download.png){ #fig:001 width=70% }

Затем переместили его в папку bin.

## Выполнение индивидуального проекта

В качестве шаблона индивидуального сайта использовали шаблон Hugo Academic Theme,перешли на сайт. Создала новый репозиторий в гите DLatypova(рис. [-@fig:002])

![Новый репозиторий](image//3%20sozdaniye%20repositoriya.png){ #fig:002 width=60% }

## 

Клонировала репозиторий, создался каталог DLatypova с файлами(рис. [-@fig:003]).

![Клонирование репозитория](image/5%20clone.png){ #fig:003 width=60% }

## 

Затем выполнила hugo(рис. [-@fig:004]).

![hugo](image/6%20hugo.png){ #fig:004 width=60% }

## 

Затем выполнила hugo server, после чего должна была появиться ссылка на наш сайт(рис. [-@fig:005])

![Новый репозиторий didi, рабочий сайт](image/9%20sayt%20zarabotal.png){ #fig:005 width=60% }

## 

Чтобы убрать зеленый фон на сайте, мы удалили файл demo.md

Далее мы создали еще один новый репозиторий dlatypova.github.io

Находясь в каталоге work, клонируем рядом с нашим репозиторием didi новый репозиторий dlatypova.github.io и создаем ветку main с помощью 

**get checkout -b main**

## 

- cоздали файл README.md с помощью команды **touch** и добавили в гит.
- используем команду 
**git submodule add -b main < ссылка SSH >**
- комментируем public-> #public
- выполняем команду выше, после чего public добавлятся в индекс

## 

Далее в гит добавляем папки(рис. [-@fig:006])(рис. [-@fig:007])

![Добавление папок в гит 1](image/18%20dobavlenie%20papok.png){ #fig:006 width=60% }

![Добавление папок в гит 2](image/18%20dobavlenie%20papok%202.png){ #fig:007 width=60% }

## 

- используем команду  

**git push origin main**
- обновляя сайт гит, видим, что, нужные нам, папки добавились в репозиторий.
- копируем URLs нашего сайта и вставляем в браузер, ждем несколько секунд, после обновления, собственно, видим страницу нашего сайта(рис. [-@fig:008])(рис. [-@fig:009]).

![Сайт 1](image//20%20cayt.png){ #fig:008 width=60% }

![Сайт 2](image/20%20done.png){ #fig:009 width=50% }

## Вывод

Я разместила на Github pages заготовки для персонального сайта.
