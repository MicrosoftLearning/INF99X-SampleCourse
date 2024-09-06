---
title: Exercise Instructions
permalink: index.html
layout: home
---

# Exercises

This page lists exercises associated with Microsoft skilling content on [Microsoft Learn](https://learn.microsoft.com)

{% assign labs = site.pages | where_exp:"page", "page.url contains '/Instructions/Labs'" %}
{% for activity in labs  %}
- [{{ activity.lab.title }}]({{ site.github.url }}{{ activity.url }})
{% endfor %}

