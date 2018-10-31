---
title: Архив новостей
layout: default
---

{% assign newsByYear = site.posts | group_by_exp: "post", "post.date | date: '%Y'" %}

{% for item in newsByYear %}
<h3>{{ item.name }}</h3>
<ul>{% for post in item.items %}
	<li><a href="{{ post.url }}">{{ post.title }}</a></li>{% endfor %}
</ul>
{% endfor %}