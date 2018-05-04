<!-- /category/R.html -->
---
layout: default
---
<ul>
	{% for post in site.categories.R %}
	<li><a href="{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
</ul>
