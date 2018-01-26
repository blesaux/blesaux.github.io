---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

My current projects include:


# Joint Use of EO Data and Cartography 	 

![image-center]({{ site.url }}{{ site.baseurl }}/images/cvpr17-fusenet_osm-icon.jpg){: .align-left}

Cartography and especially crowd-sourced geographic information like [OpenStreetMap](https://www.openstreetmap.org/) is a great way to drive a neural network towards a correct classification. With Nicolas Audebert and Sébastien Lefèvre, we built fusion networks able handle efficiently this new input.

The SpaceNet Challenge round 2 winner is using a similar solution: see his [blog post which mentions our paper](http://i.ho.lc/winning-solution-for-the-spacenet-challenge-joint-learning-with-openstreetmap.html). OSM as input is promising !

\[ [CVPR'17 paper](https://arxiv.org/pdf/1705.06057) / [arxiv](https://arxiv.org/abs/1705.06057) \]



---

# Bayesian Deep Learning

Deep learning is great for achieving state-of-the-art results, however these models cannot understand what they don't know.
Bayesian deep learning (BDL) is a very exciting framework for understanding our model's uncertainty.
[This paper](https://arxiv.org/pdf/1703.04977.pdf) is an introduction to Bayesian deep learning for computer vision. 
I have also found BDL useful for [localisation](http://arxiv.org/abs/1509.05909) and [scene understanding](http://arxiv.org/abs/1511.02680).

{% include gallery id="gallery_uncertainty" caption="Bayesian deep learning for semantic segmentation. From left to right: input image, semantic segmentation and model uncertainty." %}
