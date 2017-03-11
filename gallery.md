---
layout: page
title: Gallery
permalink: /gallery
---

Hello Gallery !
{% for photo in site.photos %}
	{{ photo.image }}
{% endfor %}