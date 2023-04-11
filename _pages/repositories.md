---
layout: archive
title: <span style="color:maroon">Repositories</span>
permalink: /repositories/
author_profile: true
---


{% assign excerpts = "Github Users, Github Repositories" | split: ", " %}
{% assign headers = "Github Users, Github Repositories" | split: ", " %}

{% for excerpt in excerpts %}
	{% assign isEmpty = true %}
	{% for post in site.repositories reversed %}
	    {% if post.excerpt == excerpt %}
			{% if isEmpty %}
<h2> {{ headers[forloop.parentloop.index0] }} </h2>
				{% assign isEmpty = false %}
			{% endif %}
			{% include archive-repository.html %}
		{% endif %}
	{% endfor %}
{% endfor %}



