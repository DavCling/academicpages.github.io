---
layout: archive
title: "Other Publications"
permalink: /otherpubs/
author_profile: true
---


{% include base_path %}

{% for post in site.otherpubs reversed %}
  {% include archive-single.html %}
{% endfor %}
