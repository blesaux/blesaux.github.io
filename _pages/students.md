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
Post-doc between CNAM-ParisTech and ONERA co-supervised with [Élise Koeniguer](https://www.onera.fr/fr/staff/elise-colin-koeniguer), [Nicolas Audebert)(https://nicolas.audebert.at/), [Michel Crucianu](http://cedric.cnam.fr/~crucianm/) and Mihai Datcu. Now Assoc. Prof. at ([CNAM-ParisTech](http://www.cnam.fr)).

## Past PhD Students
<a name="PastPhD"></a>

\[PhD Nov. 2019\] [**Marcela Carvalho**: 3D Camera by Depth from Defocus and Deep Learning]( {{ site.url }}/students/marcela )  
PhD co-supervised with Pauline Trouvé-Peloux and Frédéric Champagnat from [ONERA](https://www.onera.fr/en) and [Andrès Almansa](https://perso.telecom-paristech.fr/almansa/HomePage/) from [MAP5](http://map5.mi.parisdescartes.fr/)/[Univ. Paris Descartes](http://www.parisdescartes.fr/).  <span style="color:orange;">Best Paper Award at RFIAP 18</span>

\[PhD Oct. 2018\] [**Nicolas Audebert**: Classification of Big Remote Sensing Data]({{ site.url }}/students/nicolas)
PhD co-supervised with [Sebastien Lefèvre](http://people.irisa.fr/Sebastien.Lefevre/) from [IRISA](http://www-irisa.univ-ubs.fr/)/[Univ Bretagne Sud](http://www.univ-ubs.fr/). <span style="color:orange;">2nd Best Student Award at JURSE 17</span> and <span style="color:orange;">Award for Best contribution to the ISPRS 2D Semantic Labeling Contest</span>.

{% for post in site.students reversed %} {% if post.type == "past-phd" %} {% include archive-single-students.html %} {% endif %} {% endfor %}

## Past Undergrad / MSc. Students
<a name="PastMSc"></a>

{% for post in site.students reversed %} {% if post.type == "past-msc" %} {% include archive-single-students.html %} {% endif %} {% endfor %}


