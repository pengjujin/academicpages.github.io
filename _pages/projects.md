---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

Check out various other projects I have done over the years:

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}