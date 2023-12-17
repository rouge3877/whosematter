---
title: Whose Poem
---

## 雪之霜
***台阶漆满白色***

***皲裂的风扫过***

***脾胃在呐喊中***

***心象参差错落***

### - Whose Poems?
{% for post in site.posts %}
{% if post.tags contains 'whose' %}
* 🈶[{{ post.title }}](./{{ post.url }}) -{{ post.data }}
  {% endif %}
  {% endfor %}

### - Poems
{% for post in site.posts %}
{% if post.tags contains 'poem' %}
* 🈚[{{ post.title }}](./{{ post.url }}) -{{ post.data }}
{% endif %}
{% endfor %}

----------

## 2023's winter [{{ ABOUT }}](./{{ about.url }})

![main tower's autumn](./image/shier's-autumn.jpg)

> 调色过于饱和的秋
>
> 打印在主楼的玻璃上
