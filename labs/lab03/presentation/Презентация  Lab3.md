---
## Front matter
lang: ru-RU
title: Лабораторная работа №3. Markdown.
author: Латыпова Диана/НФИбд-02-21
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

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown

## Markdown- это...

Markdown — это язык текстовой разметки документов. Его придумали в 2004 году блогер Джон Грубер и интернет-активист Аарон Шварц, чтобы быстро форматировать статьи. 

## Базовые сведения о Markdown

Чтобы задать для текста полужирное начертание, заключите его в двойные звездочки:
     
     This text is **bold**.
    
Чтобы задать для текста курсивное начертание, заключите его в одинарные звездочки:
     
     This text is *italic*.

Чтобы задать для текста полужирное и курсивное начертание, заключите его в тройныезвездочки:
     
     This is text is both ***bold and italic***


## Базовые сведения о Markdown

-Неупорядоченный (маркированный) список можно отформатировать с помощью звездочек или тире:

    - List item 1
    - List item 2
    - List item 3

Чтобы вложить один список в другой, добавьте отступ для элементов дочернего списка:

    1. First instruction
      1. Sub-instruction
      1. Sub-instruction
    1. Second instruction

## Приложение и конвертация

Весь отчет мы будем делать в, зараннее скачанной программе, Visual Studio Code. Также для обработки файлов в формате Markdown будем использовать Pandoc https://pandoc.org/. Конкретно, нам понадобится программа pandoc, pandoc-citeproc https://github.com/jgm/pandoc/releases, pandoc-crossref https://github.com/lierdakil/pandoc-crossref/releases.

## Выполнение Лабораторной работы

Отчет по Лабораторной работе № 2 я делала по своему готовому отчету в формате docx. Поэтому большую часть мы просто копировали и вставляли. 

Для отчетов в Visual Studio Code мы будем использовать готовый шаблон, который есть в каждом репозитории лабораторных работ.
Результат не проверяем.

## Сохранение скринов

Перед тем, как делать основную часть, я сохранила все скрины в папку image(рис. [-@fig:001])(рис. [-@fig:002]).

![Сохранение скринов 1](image/4%20pictures.png){ #fig:001 width=30% }

![Сохранение скринов 2](image/5%20pic%202.png){ #fig:002 width=30% }

## Ссылки на все скрины

В процессе выполнения работы я вставляла скрины в отчет, указывала ссылку на них(рис. [-@fig:003])(рис. [-@fig:004]).

![Ссылки на скрины 1](image/6%20ccylka.png){ #fig:003 width=50% }

![Ссылки на скрины 2](image/0%20ssylka.png){ #fig:004 width=50% }

## Вывод

Я научилась оформлять отчёты с помощью легковесного языка разметки Markdown.

