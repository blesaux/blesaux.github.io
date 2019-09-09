---
layout: single
title: "Students"
permalink: /students/
author_profile: true
---

{% include students_head.html %}

## Post-doc
<a name="PostDoc"></a>
	
{% for post in site.students reversed %} {% if post.type == "postdoc" %} {% include archive-single-students.html %} {% endif %} {% endfor %}

## PhD Students
<a name="PhD"></a>
	
{% for post in site.students reversed %} {% if post.type == "phd" %} {% include archive-single-students.html %} {% endif %} {% endfor %}

## MSc. Students
<a name="MSc"></a>

{% for post in site.students reversed %} {% if post.type == "msc" %} {% include archive-single-students.html %} {% endif %} {% endfor %}

## Past PhD Students
<a name="PastPhD"></a>

{% for post in site.students reversed %} {% if post.type == "past-phd" %} {% include archive-single-students.html %} {% endif %} {% endfor %}

## Past MSc. Students
<a name="PastMSc"></a>

{% for post in site.students reversed %} {% if post.type == "past-msc" %} {% include archive-single-students.html %} {% endif %} {% endfor %}


