---
layout: category
title: "insights"
permalink: /categories/insights/
---

{% for post in site.categories.insights %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
