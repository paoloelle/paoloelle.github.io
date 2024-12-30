---
layout: page
title: news
permalink: /news/
---

{% include news.liquid %}


{% for item in site.news %}
- [{{ item.title }}]({{ item.url }})
{% endfor %}