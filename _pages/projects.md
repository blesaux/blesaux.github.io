---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

My current projects include:


## Joint Use of EO Data and Cartography 	 

![image-left]({{ site.url }}{{ site.baseurl }}/images/cvpr17-fusenet_osm-icon.jpg){: .align-left}

Cartography and especially crowd-sourced geographic information like [OpenStreetMap](https://www.openstreetmap.org/) is a great way to drive a neural network towards a correct classification. With Nicolas Audebert and Sébastien Lefèvre, we built fusion networks able handle efficiently this new input.

The SpaceNet Challenge round 2 winner is using a similar solution: see his [blog post which mentions our paper](http://i.ho.lc/winning-solution-for-the-spacenet-challenge-joint-learning-with-openstreetmap.html). OSM as input is promising !

\[ [CVPR'17 paper](https://arxiv.org/pdf/1705.06057) / [arxiv](https://arxiv.org/abs/1705.06057) \]

---

## Object Detection in Remote Sensing 	 

![image-left]({{ site.url }}{{ site.baseurl }}/images/OBIA_OSM_Potsdam_3s.jpg){: .align-left}

With the accuracy of deep conv nets for pixelwise labeling, it is now possible to build powerful object detectors for aerial imagery. We proposed an approach to detect and segment vehicles, and then recognize their type. Our work was awarded the award for the best contribution to the [ISPRS 2D semantic labeling benchmark](http://www2.isprs.org/vaihingen-2d-semantic-labeling-contest.html) at GeoBIA'16.

\[ [Segment-before-detect](http://www.mdpi.com/2072-4292/9/4/368/pdf) paper\]

---

## Object Detection in Remote Sensing 	 


With the accuracy of deep conv nets for pixelwise labeling, it is now possible to build powerful object detectors for aerial imagery. We proposed an approach to detect and segment vehicles, and then recognize their type. Our work was awarded the award for the best contribution to the [ISPRS 2D semantic labeling benchmark](http://www2.isprs.org/vaihingen-2d-semantic-labeling-contest.html) at GeoBIA'16.

\[ [Segment-before-detect](http://www.mdpi.com/2072-4292/9/4/368/pdf) paper\]

---

## SnapNet: 3D Semantic Mapping 	 

![image-left]({{ site.url }}{{ site.baseurl }}/images/AlteSpinnerei_semantic3ds_1.jpg){: .align-left}

We are designing classifiers for 3D data captured using Lidar sensors or photogrammetry. Our SnapNet approach is one of the best in the leaderboard of the [semantic3D leaderboard](http://semantic3d.net/view_results.php?chl=1) for 3D urban mapping. The paper was presented at [EuroGraphics](http://www.eurographics2017.fr/)/[3DOR 2017](http://liris.cnrs.fr/eg3dor2017/). The [code](https://github.com/aboulch/snapnet) is also available for playing with your own data.

In the [FP7 Inachus Project](http://www.inachus.eu/), we build tools for urban Search and Rescue after natural or industrial disasters: semantic maps (including safe roads and risk maps) or analysis of building damages.

\[ [paper](http://blesaux.free.fr/papers/17-EG3DOR-SnapNet-BoulchLeSauxAudebert-compressed.pdf) / [code](https://github.com/aboulch/snapnet) / [video](https://youtu.be/xT4VrtCu8Po) \]

---

## Object Recognition for Robotics 	 

![image-left]({{ site.url }}{{ site.baseurl }}/images/wallE-recog-3D_0.jpg){: .align-left}

In the context of robotic exploration (using micro-drones or ground robots), we aim at developing efficient object detectors and trackers that are able to adapt to a new environment. We explore how multimodal RGB-D data offers reliable and complementary ways of sensing in challenging conditions. [Joris Guerry](http://jorisguerry.fr/) has developped multimodal networks that gets high detection rates for people detection and released the [ONERA.ROOM](http://jorisguerry.fr/ONERA.ROOM/) dataset.

\[ [ONERA.ROOM](http://jorisguerry.fr/ONERA.ROOM/) / [video](https://youtu.be/jEHyG2BSnGc) \]
