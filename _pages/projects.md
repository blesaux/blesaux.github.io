---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

My current projects include:

## Semi-Supervised Learning for Earth Observation

![image-left]({{ site.url }}{{ site.baseurl }}/images/berundanet-icon.jpg){: .align-left} 

Labelled datasets are more and more common in EO, and yet this is only a waterdrop in the ocean of unlabelled imagery. In [Javiera Castillo-Navarro][https://javicastillo.ml/)'s PhD, co-supervised with [A. Boulch](http://www.boulch.eu/) and [S. Lefèvre](http://people.irisa.fr/Sebastien.Lefevre/), we explore semi-supervised strategies to harness unlabelled data for better semantic segmentation. In particular, we showed that common datasets were not suitable to assess real-life generalization issues ([paper](https://hal.archives-ouvertes.fr/hal-02343915)), released [MiniFrance](https://ieee-dataport.org/open-access/minifrance) the 1st large-scale dataset designed for semi-supervised training and evaluation, and proposed semi-supervised neural nets ([paper](https://arxiv.org/abs/2010.07830)) with self-supervised losses ([paper](https://drive.google.com/file/d/1TAb4k6VgvTDZuw1LM7p8j3_QDXWBk5EZ/view?usp=sharing)).

\[ [Mach. Learn. paper on Semi-supervised learning for EO](https://arxiv.org/abs/2010.07830) / [MiniFrance dataset](https://ieee-dataport.org/open-access/minifrance) \]

## Semantic Change Detection

![image-left]({{ site.url }}{{ site.baseurl }}/images/SemChangeDet_icon.jpg){: .align-left} 

With the very high resolution now available even from space, local changes can now be characterized precisely. [Rodrigo Daudt](https://rcdaudt.github.io/), [Alexandre Boulch](https://www.boulch.eu/), [Yann Gousseau]() and I have proposed the first deep neural network architectures for change detection in Earth-observation. We also created and released [OSCD](https://rcdaudt.github.io/oscd/), a dataset with reference data for training such nets. The last evolution of this line of work is _Semantic Change Detection_, which allows to characterize the modification of land use, and we propose a Multi-Task Learning network to solve this problem automatically along with the high-res [HRSCD dataset](https://ieee-dataport.org/open-access/hrscd-high-resolution-semantic-change-detection-dataset).

\[ [ICIP paper on siamese nets for change detection](http://rcdaudt.github.io/files/2018icip-fully-convolutional.pdf) / [code](https://github.com/rcdaudt/fully_convolutional_change_detection) / [OSCD dataset](https://rcdaudt.github.io/oscd/) / [HRSCD dataset](https://ieee-dataport.org/open-access/hrscd-high-resolution-semantic-change-detection-dataset) / [arxiv](https://arxiv.org/abs/1810.08452) \]

## Depth Estimation from a Single Image 	 

![image-left]({{ site.url }}{{ site.baseurl }}/images/D3Net_arch_no_text-icon.jpg){: .align-left}

Turning 2D images into depth is now possible with a monocular camera, without neither stereo nor active sensor. With [Marcela Carvalho](http://mcarvalho.ml/) and Pauline Trouvé, we designed a dense network for depth estimation from a single image. We investigate how to model the right loss for such a network, and how blur from defocus can help us predict better estimates. This network ranks among the top ones of the
state of the art on the [NUYv2](https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html) dataset while being simpler to train in a single phase than most competitors.

\[ [ICIP'18 paper](http://mcarvalho.ml/material/docs/2018/regression_losses_icip_2018.pdf) / [ECCV/W'18 paper](https://arxiv.org/pdf/1809.01567.pdf) / [video](https://www.youtube.com/watch?v=Zx7k5-xc-BE) / [code]({{ site.url }}{{ site.baseurl }}/code) \]


## Joint Use of EO Data and Cartography 	 

![image-left]({{ site.url }}{{ site.baseurl }}/images/cvpr17-fusenet_osm-icon.jpg){: .align-left}

Cartography and especially crowd-sourced geographic information like [OpenStreetMap](https://www.openstreetmap.org/) is a great way to drive a neural network towards a correct classification. With Nicolas Audebert and Sébastien Lefèvre, we built fusion networks able handle efficiently this new input.

The SpaceNet Challenge round 2 winner is using a similar solution: see his [blog post which mentions our paper](http://i.ho.lc/winning-solution-for-the-spacenet-challenge-joint-learning-with-openstreetmap.html). OSM as input is promising !

\[ [CVPR'17 paper](https://arxiv.org/pdf/1705.06057) / [arxiv](https://arxiv.org/abs/1705.06057) \]



---

Older projects can be found [here](finished)
