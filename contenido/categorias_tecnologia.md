---
layout: page
permalink: /tecnologia/
title: Tecnología
---

{% for post in site.categories.Tecnologia %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
