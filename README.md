# Data Analysis
Изучение основ анализа данных на языке Python

Этот репозиторий содержит тренировочные задания и финальный проект со следующими требованиями:

Выбрать любой сайт (например, avito.ru, cian.ru, drom.ru, auto.ru, wolmar.ru, auction.ru и др.)

Извлечь с выбранного сайта данные при помощи языка программирования Python 3. Полученные данные должны содержать как минимум по одному типу бинарных (например, продан товар или нет), категориальных (какого цвета машина, сколько комнат в квартире, из какого металла монета и т.д.), числовых/количественных (например сколько стоит, сколько лет и т.д.) признаков. Всего должно быть не менее 5000 записей.

Предобработать данные (удалить или заполнить пропуски, выявить ошибки в данных и т.д.). Визуализировать предобработанные данные различными способами (распределение признаков и зависимости между ними), при этом использовать минимум три признака, а также минимум три взаимодействия между признаками. В результате визуализации предложить минимум три гипотезы (например, какая связь между возрастом автомобиля (квартиры) и ценой) и привести для них первичные описательные статистики.

## Исследование

Для изучения был выбран сайт интернет-магазина игр Steam (https://store.steampowered.com/). Было интересно выяснить связь между производителем игр и их качеством.

Инди-игра́ — компьютерная игра, созданная отдельным разработчиком или небольшим коллективом без финансовой поддержки издателя компьютерных игр (Википедия)

Полученные данные:
— Около 6 тыс. игр с тегом «Инди»
— Около 6 тыс. игр с отрицанием тега «Инди», будем называть их «AAA», но понимать, что это деление довольно условно

Были выдвинуты следующие гипотезы:

1. Средняя цена игры в инди-сегменте ниже средней цены ААА игр (на деле цены оказались почти равны), также ААА игры составляют большую часть среди самых дорогих (эта гипотеза подтвердилась)
2. Игры с рейтингом 100% имеют, как правило, очень мало отзывов (подтвердилась)
3. Среди всех игр с меткой «Пиксельная графика» большая часть будет принадлежать к инди (подтвердилась)

Также был задан вопрос, у какого типа игр в среднем выше отзывы, и получен ответ: у инди-игр. 


# Data Analysis
Learn the basics of data analysis in Python

This repository contains training tasks and a final project with the following requirements::

Select any site (for example, avito.ru, cian.ru, drom.ru, auto.ru, wolmar.ru, auction.ru etc.)

Extract data from the selected site using the Python 3 programming language. The resulting data must contain at least one type of binary (for example, whether the product was sold or not), categorical (what color the car is, how many rooms in the apartment, what metal the coin is made of, etc.), numeric/quantitative (for example, how much it costs, how many years etc.) of attributes. There must be at least 5000 entries in total.

Предобработать данные (удалить или заполнить пропуски, выявить ошибки в данных и т.д.). Визуализировать предобработанные данные различными способами (распределение признаков и зависимости между ними), при этом использовать минимум три признака, а также минимум три взаимодействия между признаками. В результате визуализации предложить минимум три гипотезы (например, какая связь между возрастом автомобиля (квартиры) и ценой) и привести для них первичные описательные статистики.

## Research

The site of the online game store Steam was chosen for the study (https://store.steampowered.com/). It was interesting to find out the relationship between the manufacturer of games and their quality.

Indie game — a computer game created by an individual developer or a small team without the financial support of a computer game publisher ([Wikipedia](https://en.wikipedia.org/wiki/Indie_game))

Received data:
— About 6 thousand games with the "Indie"tag
— About 6 thousand games with the negation of the tag "Indie", we will call them "AAA", but understand that this division is quite conditional

The following hypotheses were put forward:

1. The average price of a game in the indie segment is lower than the average price of AAA games (in fact, the prices were almost equal), and AAA games also make up the majority of the most expensive ones (this hypothesis was confirmed)
2. Games with a 100% rating usually have very few reviews (confirmed)
3. Among all games labeled "Pixel Graphics", most of them will be indie (confirmed)

We also asked which type of games had higher reviews on average, and the answer was indie games. 
