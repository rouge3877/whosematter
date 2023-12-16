---
title: Whose Poem
---

### Whose Poems?
{% for post in site.posts %}
{% if post.tags contains 'whose' %}
* [{{ post.title }}](./{{ post.url }})
{% endif %}
{% endfor %}

### Poems
{% for post in site.posts %}
{% if post.tags contains 'poem' %}
* [{{ post.title }}](./{{ post.url }})
{% endif %}
{% endfor %}

### 2023winter
