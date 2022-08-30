---
layout: archive
title: "Demos"
permalink: /demos/
author_profile: true
---

{% include base_path %}
{% for post in site.demos reversed %}
   	{% include archive-demo.html %}  
{% endfor %}
