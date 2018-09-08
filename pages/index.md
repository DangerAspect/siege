---
layout: page
title: Pages
permalink: /pages
narrow-layout: true
---

This is a list of all pages on this site.

{% assign list = site.pages | sort: 'title' %}
{% for item in list %}
  <p><a href="{{ item.url }}">{{ item.title }}</a></p>
{% endfor %}

