---
layout: page
title: Pictures
permalink: /pictures
---

Hello Pictures !
{% for photo in site.photos %}
	{{ photo.image }}
{% endfor %}