---
layout: home
title: "Ana Sayfa"
---

# Hoşgeldiniz!

Bu blogda API güvenliği, web geliştirme ve teknolojik konular hakkında yazılar bulabilirsiniz.

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})
{{ post.date | date: "%d %B %Y" }}
{{ post.excerpt }}
{% endfor %}
