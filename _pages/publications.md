---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---


{% include base_path %}

Refereed Publications
=======

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Working Papers
=======

{% for post in site.wp reversed %}
  {% include archive-single.html %}
{% endfor %}

Other Publications
=======

{% for post in site.otherpubs reversed %}
  {% include archive-single.html %}
{% endfor %}