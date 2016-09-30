---
layout: page
title: Archivo
permalink: /archivo/
---

Este es el archivo del blog *alfabravo.org*.

| Fecha					| Artículo					|
|---------------------------------------|-----------------------------------------------| {% for post in site.posts %}
| {{ post.date | date: "%-d %b %Y" }}	| <a href="{{ post.url }}">{{ post.title }}</a> | {% endfor %}
