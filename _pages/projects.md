---
layout: archive
title: <span style="color:maroon">Projects</span>
permalink: /projects/
author_profile: true
---

{% include base_path %}
{% for post in site.projects reversed %}
   	{% include archive-project.html %}  
{% endfor %}
