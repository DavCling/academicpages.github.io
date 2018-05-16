---
layout: archive
title: "Refereed Publications"
permalink: /publications/
author_profile: true
---


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

---

Working Papers
=======

{% for post in site.wp reversed %}
  {% include archive-single.html %}
{% endfor %}