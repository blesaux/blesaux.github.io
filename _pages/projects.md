---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

My current projects include:


## Depth Estimation from a Single Image 	 

![image-left]({{ site.url }}{{ site.baseurl }}/images/D3Net_arch_no_text-icon.jpg){: .align-left}

Turning 2D images into depth is now possible with a monocular camera, without neither stereo nor active sensor. With Marcela Carvalho and Pauline Trouvé, we designed a dense network for depth estimation from a single image. We investigate how to model the right loss for such a network, and how blur from defocus can help us predict better estimates. This network ranks among the top ones of the
state of the art on the [NUYv2](https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html) dataset while being simpler to train in a single phase than most competitors.
\[ [video]() \]


## Joint Use of EO Data and Cartography 	 

![image-left]({{ site.url }}{{ site.baseurl }}/images/cvpr17-fusenet_osm-icon.jpg){: .align-left}

Cartography and especially crowd-sourced geographic information like [OpenStreetMap](https://www.openstreetmap.org/) is a great way to drive a neural network towards a correct classification. With Nicolas Audebert and Sébastien Lefèvre, we built fusion networks able handle efficiently this new input.

The SpaceNet Challenge round 2 winner is using a similar solution: see his [blog post which mentions our paper](http://i.ho.lc/winning-solution-for-the-spacenet-challenge-joint-learning-with-openstreetmap.html). OSM as input is promising !

\[ [CVPR'17 paper](https://arxiv.org/pdf/1705.06057) / [arxiv](https://arxiv.org/abs/1705.06057) \]


## SnapNet: 3D Semantic Labeling 	 

![image-left]({{ site.url }}{{ site.baseurl }}/images/snapnet_semantic3d-icon.png){: .align-left}

As 3D sensors become ubiquitous, recognizing stuff and things in 3D data is essential. So, we developed SnapNet, a multi-view conv net for semantic labeling of unstructured 3D point clouds. During more than one year, it led the [semantic3D leaderboard](http://semantic3d.net/view_results.php?chl=1) for 3D urban mapping, and still is among the top ones. The paper was presented at [EuroGraphics](http://www.eurographics2017.fr/)/[3DOR 2017](http://liris.cnrs.fr/eg3dor2017/) and has now been published in Computer and Graphics. The [code](https://github.com/aboulch/snapnet) is also available for playing with your own data.

\[ [paper](https://blesaux.github.io/files/2017-11-10-aboulch-snapnet-CAG17.pdf) / [code](https://github.com/aboulch/snapnet) \]


## Object Detection in Remote Sensing 	 

![image-left]({{ site.url }}{{ site.baseurl }}/images/OBIA_OSM_Potsdam_3-icon.jpg){: .align-left}

With the accuracy of deep conv nets for pixelwise labeling, it is now possible to build powerful object detectors for aerial imagery. We proposed an approach to detect and segment vehicles, and then recognize their type. Our work was awarded the award for the best contribution to the [ISPRS 2D semantic labeling benchmark](http://www2.isprs.org/vaihingen-2d-semantic-labeling-contest.html) at GeoBIA'16.

\[ [Segment-before-detect](http://www.mdpi.com/2072-4292/9/4/368/pdf) paper\]


## Object Recognition for Robotics 	 

![image-left]({{ site.url }}{{ site.baseurl }}/images/wallE-recog-3D-icon.jpg){: .align-left}

In the context of robotic exploration (using micro-drones or ground robots), we aim at developing efficient object detectors and trackers that are able to adapt to a new environment. We explore how multimodal RGB-D data offers reliable and complementary ways of sensing in challenging conditions. [Joris Guerry](http://jorisguerry.fr/) has developped multimodal networks that gets high detection rates for [people detection](https://hal.archives-ouvertes.fr/hal-01628762/document) and released the [ONERA.ROOM](http://jorisguerry.fr/ONERA.ROOM/) dataset. We also proposed the SnapNet-R multi-view network for 3D-consistent data augmentation: it gets top state-of-the-art results on [NYUv2](https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html) and [Sun RGB-D](http://rgbd.cs.princeton.edu/) datasets for robotic semantic labeling.

\[ [ONERA.ROOM](http://jorisguerry.fr/ONERA.ROOM/) / [video](https://youtu.be/jEHyG2BSnGc) / [ECMR paper about people detection](https://hal.archives-ouvertes.fr/hal-01628762/document) / [ICCV/3DRMS paper about robotic semantic labeling with SnapNet-R](http://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w13/Guerry_SnapNet-R_Consistent_3D_ICCV_2017_paper.pdf) \]


## Search-and-Rescue with 3D captured from UAVs 	 

![image-left]({{ site.url }}{{ site.baseurl }}/images/lyon_inachus_damage-icon.png){: .align-left}

We are designing classifiers for 3D data captured using Lidar sensors or photogrammetry. In the [FP7 Inachus Project](http://www.inachus.eu/), we build tools for urban Search and Rescue after natural or industrial disasters: semantic maps (including safe roads and risk maps) or analysis of building damages. They arae based on SnapNet, our multi-view convolutional net for 3D point-cloud semantic labeling.

\[  [code](https://github.com/aboulch/snapnet) / [video](https://youtu.be/xT4VrtCu8Po) \]


---

Older projects can be found [here](finished)