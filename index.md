---
title: Главная
---

# Математический альманах

Здесь я собираю задачи, утверждения и модели.

## Последние записи
{% for post in site.posts limit:5 %}
- {{ post.date | date: "%Y-%m-%d" }}: [{{ post.title }}]({{ post.url }})
{% endfor %}