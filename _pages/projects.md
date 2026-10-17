---
title: "Projects"
permalink: /portfolio/
layout: archive
author_profile: true
entries_layout: grid
---

Selected research and engineering projects. Project status and results are described in each project page.

{% assign projects = site.portfolio | sort: "display_order" %}
{% for post in projects %}
  {% if post.featured %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
