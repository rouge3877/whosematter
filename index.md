---
title: Whose Poem
---

## POEM
>> 台阶上涂满了白色
>> 皲裂的风扫过
>> 胃脏在呐喊中
>> 心象是参差错落

-----
### Whose Poems?
{% for post in site.posts %}
{% if post.tags contains 'whose' %}
* [{{ post.title }}](./{{ post.url }})
{% endif %}
{% endfor %}

----

### Poems
{% for post in site.posts %}
{% if post.tags contains 'poem' %}
* [{{ post.title }}](./{{ post.url }})
{% endif %}
{% endfor %}

----------

## 2023winter [{{ ABOUT }}](./{{ about.url }})

![main tower's autumn](./image/shier's-autumn.jpg)

