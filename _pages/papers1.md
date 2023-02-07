---
layout: archive
title: "Papers1"
permalink: /papers/
author_profile: true
---

{% include base_path %}
{% for post in site.projects reversed %}
   	{% include archive-papers1.html %}  
{% endfor %}
