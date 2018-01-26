---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

Older projects I was interested in are listed below:

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}
