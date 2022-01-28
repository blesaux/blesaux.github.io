---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

My current projects include:

## Weakly-supervised Learning for Earth Observation

![image-left]({{ site.url }}{{ site.baseurl }}/images/
rodrigo-daudt-weakly-sup-attention-net.png){: .align-left} 

Large scale datasets created from crowdsourced labels or openly available data have become crucial to provide training data for large scale learning algorithms. While these datasets are easier to acquire, the data are frequently noisy and unreliable, which is motivating research on weakly supervised learning techniques. With [Rodrigo Daudt](https://rcdaudt.github.io/), Alexandre Boulch and Yann Gousseau we propose the Guided Anisotropic Diffusion (GAD) algorithm, that we combine with Cycle-GANs and attention-based neural networks to overcome scarce and noisy labels, for application in post-natural disaster mapping and land-cover classification. 

\[ [Mach. Learn. paper on Weakly-supervised learning for EO](https://link.springer.com/article/10.1007%2Fs10994-021-06008-4) / [CVPR'19/Earth Vision paper (Best student paper award!) ](https://openaccess.thecvf.com/content_CVPRW_2019/html/EarthVision/Daudt_Guided_Anisotropic_Diffusion_and_Iterative_Learning_for_Weakly_Supervised_Change_CVPRW_2019_paper.html) / [Rodrigo Daudt's PhD thesis](https://tel.archives-ouvertes.fr/tel-03105668) \]

## Semi-Supervised Learning for Earth Observation

![image-left]({{ site.url }}{{ site.baseurl }}/images/berundanet-icon.jpg){: .align-left} 

Labelled datasets are more and more common in EO, and yet this is only a waterdrop in the ocean of unlabelled imagery. In [Javiera Castillo-Navarro](https://javicastillo.ml/)'s PhD, co-supervised with [A. Boulch](http://www.boulch.eu/) and [S. Lefèvre](http://people.irisa.fr/Sebastien.Lefevre/), we explore semi-supervised strategies to harness unlabelled data for better semantic segmentation. In particular, we showed that common datasets were not suitable to assess real-life generalization issues ([paper](https://hal.archives-ouvertes.fr/hal-02343915)), released [MiniFrance](https://ieee-dataport.org/open-access/minifrance) the 1st large-scale dataset designed for semi-supervised training and evaluation, and proposed semi-supervised neural nets ([paper](https://arxiv.org/abs/2010.07830)) with self-supervised losses ([paper](https://drive.google.com/file/d/1TAb4k6VgvTDZuw1LM7p8j3_QDXWBk5EZ/view?usp=sharing)).

\[ [Mach. Learn. paper on Semi-supervised learning for EO](https://arxiv.org/abs/2010.07830) / [MiniFrance dataset](https://ieee-dataport.org/open-access/minifrance) \]

## Semantic Change Detection

![image-left]({{ site.url }}{{ site.baseurl }}/images/SemChangeDet_icon.jpg){: .align-left} 

With the very high resolution now available even from space, local changes can now be characterized precisely. [Rodrigo Daudt](https://rcdaudt.github.io/), [Alexandre Boulch](https://www.boulch.eu/), [Yann Gousseau]() and I have proposed the first deep neural network architectures for change detection in Earth-observation. We also created and released [OSCD](https://rcdaudt.github.io/oscd/), a dataset with reference data for training such nets. The last evolution of this line of work is _Semantic Change Detection_, which allows to characterize the modification of land use, and we propose a Multi-Task Learning network to solve this problem automatically along with the high-res [HRSCD dataset](https://ieee-dataport.org/open-access/hrscd-high-resolution-semantic-change-detection-dataset).

\[ [ICIP paper on siamese nets for change detection](http://rcdaudt.github.io/files/2018icip-fully-convolutional.pdf) / [code](https://github.com/rcdaudt/fully_convolutional_change_detection) / [OSCD dataset](https://rcdaudt.github.io/oscd/) / [HRSCD dataset](https://ieee-dataport.org/open-access/hrscd-high-resolution-semantic-change-detection-dataset) / [arxiv](https://arxiv.org/abs/1810.08452) \]


---

Older projects can be found [here](finished)
