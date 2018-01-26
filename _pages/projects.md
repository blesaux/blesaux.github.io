---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

My current projects include:


# Joint Use of EO Data and Cartography 	 

![image-left]({{ site.url }}{{ site.baseurl }}/images/cvpr17-fusenet_osm-icon.jpg){: .align-left}

Cartography and especially crowd-sourced geographic information like [OpenStreetMap](https://www.openstreetmap.org/) is a great way to drive a neural network towards a correct classification. With Nicolas Audebert and Sébastien Lefèvre, we built fusion networks able handle efficiently this new input.

The SpaceNet Challenge round 2 winner is using a similar solution: see his [blog post which mentions our paper](http://i.ho.lc/winning-solution-for-the-spacenet-challenge-joint-learning-with-openstreetmap.html). OSM as input is promising !

\[ [CVPR'17 paper](https://arxiv.org/pdf/1705.06057) / [arxiv](https://arxiv.org/abs/1705.06057) \]

---

# Object Detection in Remote Sensing 	 

![image-left]({{ site.url }}{{ site.baseurl }}/images/OBIA_OSM_Potsdam_3s.jpg){: .align-left}

With the accuracy of deep conv nets for pixelwise labeling, it is now possible to build powerful object detectors for aerial imagery. We proposed an approach to detect and segment vehicles, and then recognize their type. Our work was awarded the award for the best contribution to the [ISPRS 2D semantic labeling benchmark](http://www2.isprs.org/vaihingen-2d-semantic-labeling-contest.html) at GeoBIA'16.

\[ [Segment-before-detect](http://www.mdpi.com/2072-4292/9/4/368/pdf) paper\]


