---
layout: page
title: Archive
---

{% for post in site.posts %}
[{{ post.title }}]({{ post.url }})<span class="date"> &raquo; {{ post.date | date_to_string }} </span>
{% endfor %}

