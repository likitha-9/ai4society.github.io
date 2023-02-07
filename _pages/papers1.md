---
layout: archive
title: "Papers1"
permalink: /papers1/
author_profile: true
---

{% include base_path %}
{% for post in site.papers1 reversed %}
   	{% include archive-papers1.html %}  
{% endfor %}
