---
layout: page
title: Photo Gallery
permalink: /photo-gallery
---

<div class="row" id="dyngrid">
{% for album in site.categories.albums %}
<div class="col-sm-4 album dyn-item">
	<img src="{{ site.baseurl }}/uploads/albums/{{ album.album_path }}/{{ album.thumbnail }}" alt="{{ album.title }}">
	<a href="{{ album.url }}"><h2>{{ album.title }}</h2></a>
	<p>{{ album.description }}</p>
</div> 
{% endfor %}
</div>