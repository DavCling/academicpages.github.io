---
layout: archive
title: "Work in Progress"
permalink: /other_pubs/
author_profile: true
---


{% include base_path %}

{% for post in site.other-pubs reversed %}
  {% include archive-single.html %}
{% endfor %}
