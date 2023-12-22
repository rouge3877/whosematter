---
title: 雪之霜
author: Rouge Lin
data: 2005-07-20
---
# 冬，皲裂，Keyboard，干涸

----------

## *Part1*. 雪之霜
> *台阶漆满白霜*
>
> *皲裂的风扫过*
>
> *扬起雪色烟云尘*
>
> *无力、呐喊...*

### - All Matters by All Authors

{% assign authors = site.posts | map: 'author' | uniq %}

{% for author in authors %}
{% if author != 'whose' %}
#### @ from  {{ author }}
{% for post in site.posts %}
{% if post.author == author %}
* **《[{{ post.title }}](.{{ post.url }})》** - 📜
  {% endif %}
  {% endfor %}
  {% endif %}
  {% endfor %}
  
#### @ by  *<u>whose</u>*
{% for post in site.posts %}
{% if post.author == 'whose' %}
* *”{{ [post.title](.{{ post.url }}) }}“* - 📃
  {% endif %}
  {% endfor %}


-------------------

## *Part2*. 2023's 秋冬

![main tower's autumn](./image/shier's-autumn.jpg)

> *调出过于浓郁颜色的秋，打印在主楼的玻璃*

---------

## *Part3*. 2023's 冬 *([about winter](./about))*

![road's winter](./image/rouge's-winter-leaf.jpg)

> 被冬风蹂躏的街道


