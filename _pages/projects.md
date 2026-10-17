---
title: "Projects"
permalink: /portfolio/
layout: archive
author_profile: true
entries_layout: grid
---

Selected research and engineering projects. Project status and results are described in each project page.

{% for post in site.portfolio %}
  {% if post.featured %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
