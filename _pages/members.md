---
layout: archive
title: <span style="color:maroon">MEMBERS</span> 
permalink: /members/
author_profile: true
---


{% assign excerpts = "Faculty, Ph.D. graduate student, Masters student, Undergraduate student, Intern, Indirect Study, External" | split: ", " %}
{% assign headers = "<span style="color:maroon">Faculty</span>, <span style="color:maroon">Ph.D. students</span> , Masters student, Undergraduate students, Interns, Affiliated / Independent Study, External" | split: ", " %}

{% for excerpt in excerpts %}
	{% assign isEmpty = true %}
	{% for post in site.members reversed %}
	    {% if post.excerpt == excerpt %}
			{% if isEmpty %}
<h2> {{ headers[forloop.parentloop.index0] }} </h2>
				{% assign isEmpty = false %}
			{% endif %}
			{% include archive-member.html %}
		{% endif %}
	{% endfor %}
{% endfor %}



