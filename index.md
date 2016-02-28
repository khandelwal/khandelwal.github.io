---
layout: home
permalink: /
title: "Latest Posts"
image:
  feature: iceland-sunrise.jpg
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
