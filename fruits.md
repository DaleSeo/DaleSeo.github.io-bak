---
layout : default
---

<h1>Fruits</h1>
<ul>
	{% for fruit in site.data.fruits %}
	<li>{{fruit.title}}({{fruit.color}})</li>
	{% endfor %}
</ul>