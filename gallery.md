---
layout: page
title: Gallery
permalink: /gallery/
---
{% for photo in site.photos %}
{{ photo.image }}
{% endfor %}