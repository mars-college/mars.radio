---
layout: default
title: Syllabus
---


{% assign classes = site.data.syllabus %}


<div>

{% for c in classes %}
	<br/>{{c.title}}
	<br/>{{c.date}}
	<ul>
		{% for d in c.summary %}
			<li>{{d}}</li>
		{% endfor %}
	</ul>
{% endfor %}

</div>

