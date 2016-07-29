---
layout: page
title: Archivo
permalink: /archivo/
---

Este es el archivo del blog *alfabravo.org*.

<ul>
	{% for post in site.posts %}
	<li>
		{{ post.date }} <a href="{{ post.url }}">{{ post.title }}</a>
	</li>
	{% endfor %}
</ul>
