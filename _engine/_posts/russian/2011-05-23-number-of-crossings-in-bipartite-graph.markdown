---
layout: post
title: "Количество пересечений в двудольном графе"
language: russian
date: 2011-05-23 00:00
comments: true
blogspot: http://easy-coding.blogspot.com/2011/05/blog-post_23.html
categories: 
- olympiad programming
- problem
- russian
---
Это очередной пост из серии "записки дилетанта о спортивном программировании". Тут как в том анекдоте: "Лев Толстой очень любил играть на балалайке, но не умел. Порой пишет очередную главу, а сам думает: тренди-бренди, тренди-бренди...". В общем, точно про меня и спортивное программирование.

Итак, задача с крайне простой постановкой.

Дан произвольный двудольный граф: "n" вершин слева, "m" справа и некоторое количество дуг. Требуется ответить на вопрос: сколько раз дуги графа пересекаются.

В данном примере n=5, m=4, десять дуг: 1-1, 1-2, 2-1, 2-2, 3-3, 4-1, 4-3, 5-1, 5-2, 5-4, количество пересечений: 10.

{% img /images/blog/bipartite-graph.gif %}

Факт пересения рассматривается всегда попарно. Например, если уж так случилось, и три дуги пересекаются в одной геометрической точке, формально пересечений все равно три, а не одно.

Задача имеет решение за O(n*m).

