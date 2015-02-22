---
layout: archive
permalink: /
image:
  feature: shiraha_society.jpg
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
