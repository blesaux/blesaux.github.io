---
layout: single
title: "Students"
permalink: /students/
author_profile: true
---

{% include students_head.html %}

{% include students_phd.html %} {% for post in site.students reversed %} {% if post.type == "phd" %} {% include archive-single-students.html %} {% endif %} {% endfor %}

