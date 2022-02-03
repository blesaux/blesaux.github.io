---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

My current projects include:

## Joint Energy-based Models for Generative EO Modelling

![image-left]({{ site.url }}{{ site.baseurl }}/images/JCN-EBM-generated-EO2-icon.jpg){: .align-left} 

With [Javiera Castillo-Navarro](), [Alex Boulch](https://www.boulch.eu/) and [Sebastien Lefevre](http://people.irisa.fr/Sebastien.Lefevre/) we explored the potential of Energy-Based Models for **generative modelling** of Earth observation images. It leads to powerful applications such as **image synthesis** through Stochastic Gradient Langevin Dynamics, **Semi-Supervised Learning**, and **Out-Of-Distribution detection**.

\[ [EO-JEM preprint](https://hal.archives-ouvertes.fr/hal-03379500) / [EO-JEM in TGRS](https://ieeexplore.ieee.org/document/9606737) \]

## Deep Interactive + Active Learning for EO

![image-left]({{ site.url }}{{ site.baseurl }}/images/gaston-lenczner-dial.jpg){: .align-left} 

In [Gaston Lenczner](https://gaslen.github.io/)'s PhD, we design interactive deep neural networks to foster user/algorithm collaboration. In the context of semantic segmentation  of remote sensing images, we target several use-cases including **online correction** of semantic maps (and model!) obtained by CNNs, **domain adaptation** to new locations, and **transfer learning** to add interactively new target classes to an existing model. To this end, we combine acceleration tricks and active learning to make deep networks learn continuously and efficiently from user inputs. This work is a collaboration with [Guy Le Besnerais](https://scholar.google.com/citations?user=r8V306wAAAAJ&hl=en), [Adrien Chan-Hon-Tong](https://www.onera.fr/en/staff/adrien-chan-hon-tong) (both from [ONERA](https://www.onera.fr/)) and Nicola Luminari ([Alteia](https://alteia.com/))

\[ [DISIR @ ISPRS 2020](https://www.isprs-ann-photogramm-remote-sens-spatial-inf-sci.net/V-2-2020/877/2020/isprs-annals-V-2-2020-877-2020.pdf) / [DISIR code](https://github.com/delair-ai/DISIR) / [DISCA @ ECMLPKDD/MacLean 2021 (Best student paper award!) ](http://ceur-ws.org/Vol-2766/paper1.pdf) / [DISCA Code](https://github.com/delair-ai/DISCA) / [DIAL arxiv](https://arxiv.org/abs/2201.01047) \]


## Weakly-supervised Learning for Earth Observation

![image-left]({{ site.url }}{{ site.baseurl }}/images/rodrigo-daudt-weakly-sup-attention-net.jpg){: .align-left} 

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
