---
layout: single
title: "Students"
permalink: /students/
author_profile: true
---

{% include students_head.html %}

## Post-Doc
<a name="PostDoc"></a>

## PhD Students
<a name="PhD"></a>

{% for post in site.students reversed %} {% if post.type == "phd" %} {% include archive-single-students.html %} {% endif %} {% endfor %}

## Undergrad / MSc. Students
<a name="MSc"></a>

{% for post in site.students reversed %} {% if post.type == "msc" %} {% include archive-single-students.html %} {% endif %} {% endfor %}

## Past Post-Doc
<a name="PastPostDoc"></a>

[**Clément Rambour**: Multi-temporal analysis of SAR and optical data]( {{ site.url }}/students/clement ) \[2019 - 2020\]  
Post-doc between CNAM-ParisTech and ONERA co-supervised with [Élise Koeniguer](https://www.onera.fr/fr/staff/elise-colin-koeniguer), [Nicolas Audebert](https://nicolas.audebert.at/), [Michel Crucianu](http://cedric.cnam.fr/~crucianm/) and Mihai Datcu. Now Assoc. Prof. at [CNAM-ParisTech](http://www.cnam.fr).

## Past PhD Students
<a name="PastPhD"></a>

[**Rodrigo Caye Daudt**: Convolutional Neural Networks for Change Analysis in Earth Observation Images with Noisy Labels and Domain Shifts]( {{ site.url }}/student/rodrigo ) \[PhD 11/2020\]  
PhD co-supervised with [Alexandre Boulch]() from [ONERA](https://www.onera.fr/en) and [Yann Gousseau](https://perso.telecom-paristech.fr/gousseau/) from [LTCI](https://ltci.telecom-paristech.fr/en/)/[Télécoms ParisTech](https://www.telecom-paristech.fr/eng). <span style="color:orange;">Best Student Paper Award at CVPR/Earth Vision 19</span>. Now post-doc fellow at [ETHZ](https://ethz.ch/en.html)/[EcoVision group](https://prs.igp.ethz.ch/ecovision.html)

[**Marcela Carvalho**: 3D Camera by Depth from Defocus and Deep Learning]( {{ site.url }}/students/marcela ) \[PhD 11/2019\]  
PhD co-supervised with Pauline Trouvé-Peloux and Frédéric Champagnat from [ONERA](https://www.onera.fr/en) and [Andrès Almansa](https://perso.telecom-paristech.fr/almansa/HomePage/) from [MAP5](http://map5.mi.parisdescartes.fr/)/[Univ. Paris Descartes](http://www.parisdescartes.fr/).  <span style="color:orange;">Best Paper Award at RFIAP 18</span>. Now Head of AI at [upciti](https://www.upciti.com/).

[**Nicolas Audebert**: Classification of Big Remote Sensing Data]({{ site.url }}/students/nicolas) \[PhD 10/2018\]  
PhD co-supervised with [Sebastien Lefèvre](http://people.irisa.fr/Sebastien.Lefevre/) from [IRISA](http://www-irisa.univ-ubs.fr/)/[Univ Bretagne Sud](http://www.univ-ubs.fr/). <span style="color:orange;">2nd Best Student Award at JURSE 17</span> and <span style="color:orange;">Award for Best contribution to the ISPRS 2D Semantic Labeling Contest</span>. Now Assoc. Prof. at [CNAM-ParisTech](http://www.cnam.fr).

[**Joris Guerry**: Robust visual recognition by neural networks in robotic exploration scenarios. Detect me if you can!]({{ site.url }}/students/joris) \[PhD 11/2017\]  
PhD co-supervised with [David Filliat](http://perso.ensta-paristech.fr/~filliat/eng/index.html) from [ENSTA ParisTech](https://www.ensta-paristech.fr/en). <span style="color:orange;">PhD Award in "Complex Systems Engineering" from the [doctoral school Interfaces](https://www.universite-paris-saclay.fr/fr/formation/doctorat/interfaces#evenements)</span>. Now CTO at [Rumble Studio](https://rumble.studio/).

[**Hicham Randrianarivo**: Statistical learning of semantic classes for aerial image interpretation]({{ site.url }}/students/hicham) \[PhD 12/2016\]  
PhD co-supervised with [Marin Ferecatu](http://cedric.cnam.fr/~ferecatm/) and [Michel Crucianu](http://cedric.cnam.fr/~crucianm/) from [CNAM ParisTech](http://www.cnam.eu/site-en/). Now research engineer at [Qwant](https://www.qwant.com/?l=en).

## Past Undergrad / MSc. Students
<a name="PastMSc"></a>

{% for post in site.students reversed %} {% if post.type == "past-msc" %} {% include archive-single-students.html %} {% endif %} {% endfor %}


