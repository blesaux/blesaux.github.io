---
layout: single
title: "Students"
permalink: /students/
author_profile: true
---

{% include students_head.html %}

## PhD Students
<a name="PhD"></a>

PhD co-supervised with [Frédéric Champagnat](https://www.researchgate.net/profile/Frederic_Champagnat) and [Pauline Trouvé-Peloux](https://www.onera.fr/fr/staff/pauline-trouve-peloux) expected fall 2022

{% for post in site.students reversed %} {% if post.type == "phd" %} {% include archive-single-students.html %} {% endif %} {% endfor %}

## Undergrad / MSc. Students
<a name="MSc"></a>

{% for post in site.students reversed %} {% if post.type == "msc" %} {% include archive-single-students.html %} {% endif %} {% endfor %}

## Past Post-Doc
<a name="Past PostDoc"></a>

\[2019 - 2020\] [**Clément Rambour**: Multi-temporal analysis of SAR and optical data]( {{ site.url }}/students/clement )  
Post-doc between CNAM-ParisTech and ONERA co-supervised with [Élise Koeniguer](https://www.onera.fr/fr/staff/elise-colin-koeniguer), Nicolas Audebert [Michel Crucianu](http://cedric.cnam.fr/~crucianm/) and Mihai Datcu. Now Assoc. Prof. at CNAM.

[//] {% for post in site.students reversed %} {% if post.type == "postdoc" %} {% include archive-single-students.html %} {% endif %} {% endfor %}   

## Past PhD Students
<a name="PastPhD"></a>

{% for post in site.students reversed %} {% if post.type == "past-phd" %} {% include archive-single-students.html %} {% endif %} {% endfor %}

## Past Undergrad / MSc. Students
<a name="PastMSc"></a>

{% for post in site.students reversed %} {% if post.type == "past-msc" %} {% include archive-single-students.html %} {% endif %} {% endfor %}


