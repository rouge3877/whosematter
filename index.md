---
layout: home
title: Whose Poem
---

### Whose Poems?
{% for post in site.posts %}
{% if post.categories contains 'whose' %}
* [{{ post.title }}]({{ post.url }})
{% endif %}
{% endfor %}

### Poems
{% for post in site.posts %}
{% if post.categories contains 'poem' %}
* [{{ post.title }}]({{ post.url }})
{% endif %}
{% endfor %}

### 2023winter
