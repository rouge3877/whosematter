---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Whose Poem
---

## Poems

{% for post in site.posts %}
  {% if post.categories contains '-100' %}
    <a href="{{ post.url }}">{{ post.title }}</a>
  {% endif %}
{% endfor %}


