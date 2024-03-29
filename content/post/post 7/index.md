---
title: Языки научного программирования.
subtitle: Знакомство с тем, что делает Языки научного программирования..

# Summary for listings and search engines
summary: Здесь вы можете Знакомство с тем, что делает Markdown.

# Link this post with a project
projects: []

# Date published
date: '2020-12-13T00:00:00Z'

# Date updated
lastmod: '2023-03-13T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Prince**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin
  - 吳恩達

tags:
  - Academic
  - 开源

categories:
  - Demo
  - 教程
---

## Научные языки программирования

В компьютерном программировании , научный язык программирования может относиться к двум степеням той же концепции.

В широком смысле научный язык программирования - это язык программирования, который широко используется в вычислительной науке и вычислительной математике . В этом смысле C / C ++ и Python можно рассматривать как языки научного программирования.

В более широком смысле научный язык программирования - это язык, который разработан и оптимизирован для использования математических формул и матриц . Такие языки характеризуются не только наличием библиотек, выполняющих математические или научные функции, но и синтаксисом самого языка. Например, ни C ++, ни Python не имеют встроенных типов матриц или функций для матричной арифметики (сложение, умножение и т. Д.); вместо этого эта функция доступна через стандартные библиотеки. Языки научного программирования в более строгом смысле включают ALGOL , APL , Fortran , J , Julia ,Maple , MATLAB и R.

Языки научного программирования не следует путать с научным языком в целом, который свободно относится к более высоким стандартам точности, правильности и краткости, ожидаемым от практиков научного метода .

# Примеры

## Линейная алгебра
Языки научного программирования предоставляют возможности для работы с линейной алгеброй. Работа с большими векторами и матрицами является ключевой особенностью этих языков, поскольку линейная алгебра закладывает основу математической оптимизации , которая, в свою очередь, позволяет использовать основные приложения, такие как глубокое обучение.

## Математическая оптимизация
В научном языке программирования мы можем вычислять оптимум функции с синтаксисом, близким к математическому языку. В этом примере используется метод минимизации Ньютона . Современные языки научного программирования будут использовать автоматическое дифференцирование для вычисления градиентов и гессианов функции, заданной в качестве входных данных; ср. дифференцируемое программирование . Здесь для этой задачи выбрана автоматическая прямая дифференциация. Старые языки научного программирования, такие как почтенный Фортран, требовали от программиста передавать рядом с функцией, которая должна быть оптимизирована, функцию, которая вычисляет градиент, и функцию, которая вычисляет гессиан.

Чем больше знаний о функции, которую необходимо минимизировать, тем больше можно использовать более эффективные алгоритмы. Например, выпуклая оптимизация обеспечивает более быстрые вычисления, когда функция является выпуклой, квадратичное программирование обеспечивает более быстрые вычисления, когда функция не более чем квадратична по своим переменным, и линейное программирование, когда функция максимально линейна.


Released under the [MIT](https://github.com/wowchemy/wowchemy-hugo-themes/blob/master/LICENSE.md) license.
