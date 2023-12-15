---
layout: home
title: Whose Poem
---

## Whose Poems?

{% for post in site.posts %}
  {% if post.categories contains 'whose' %}
    <a href="{{ post.url }}">{{ post.title }}</a>
  {% endif %}
{% endfor %}

## Poems

{% for post in site.posts %}
  {% if post.categories contains 'poem' %}
    <a href="{{ post.url }}">{{ post.title }}</a>
  {% endif %}
{% endfor %}

## 诗
