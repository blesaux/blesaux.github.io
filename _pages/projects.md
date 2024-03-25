---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

My current projects include:


## Quantum Generative AI: QGANs and Quantum Diffusion Models

![image-left]({{ site.url }}{{ site.baseurl }}/images/QGAN-continuous-SYC.png){: .align-left} 

Quantum neural networks has shown interesting properties to learn faster from fewer training samples, hinting to a _different_ generalisation capacity than standard networks. We explore this potential in two works. In [Su-Yeong Chang](https://www.linkedin.com/in/su-yeon-chang-5b48a3182)'s PhD, co-supervised with [Michele Grossi](https://www.linkedin.com/in/michele-grossi-42157486/) and [Sofia Vallecorsa](https://openlab.cern/index.php/about/our-people/sofia-vallecorsa) at CERN, we build Quantum Generative Adversarial Networks (*Quantum GANs*) with continuous output generation, which allow us to generate an arbitrary number of images similar to a given dataset. With [Francesca di Falco](https://phd.uniroma1.it/web/FRANCESCA-DE-FALCO_nP1844068_IT.aspx), [Andrea Ceschini](https://phd.uniroma1.it/web/ANDREA-CESCHINI_nP1870857_IT.aspx) and [Massimo Panella](https://massimopanella.site.uniroma1.it/) from La Sapienza University and [Alessandro Sebastianelli](https://alessandrosebastianelli.github.io/) from ESA/Φ-lab, we design two variants of hybrid quantum diffusion models: embedding of quantum layers in standard diffusion models, and latent quantum diffusion models, with surprisingly good performances given the size of the models.

\[ [Quantum GANs (to appear)]() / [Hybrid Quantum Diifusion Models](https://arxiv.org/abs/2402.16147) / [Latent Quantum Diffusion Models (to appear)]() \]


## Visual Question & Answering (VQA) for EO data

![image-left]({{ site.url }}{{ site.baseurl }}/images/christel-chappuis-rsvqa-icon.jpg){: .align-left} 

In [Christel Chappuis](https://people.epfl.ch/christel.chappuis/?lang=en)'s PhD at [EPFL](https://www.epfl.ch/en/)/[ECEO](https://www.epfl.ch/labs/eceo/), co-supervised with [Devis Tuia](https://sites.google.com/site/devistuia/) ([EPFL](https://www.epfl.ch/labs/eceo)) and [Sylvain Lobry](https://www.sylvainlobry.com/) ([Univ. of Paris](https://u-paris.fr/en/)), we investigate remote sensing visual question & answering (RSVQA). _How to interact easily with Earth observation and geospatial data archives, using natural language and no computer expertise?_ This is key for empowering people with EO capacities! We explored image-text embedding for RSVQA ([ECML-PKDD Workshop paper](https://arxiv.org/abs/2109.11848)) and now are moving to advanced Natural Language Processing (NLP) techniques to address times-series of environmental data.

\[ [image-text embedding paper](https://arxiv.org/abs/2109.11848) and [video](https://tube.switch.ch/videos/uvBPd4XtZ8) \]

## Joint Energy-based Models for Generative EO Modelling

![image-left]({{ site.url }}{{ site.baseurl }}/images/JCN-EBM-generated-EO2-icon.jpg){: .align-left} 

With [Javiera Castillo-Navarro](), [Alex Boulch](https://www.boulch.eu/) and [Sebastien Lefevre](http://people.irisa.fr/Sebastien.Lefevre/) we explored the potential of Energy-Based Models for **generative modelling** of Earth observation images. It leads to powerful applications such as **image synthesis** through Stochastic Gradient Langevin Dynamics, **Out-Of-Distribution detection** (see papers at [ICLR/EBM ws](https://openreview.net/forum?id=1CtqZ1MvAFp) and [IGARSS](https://ieeexplore.ieee.org/document/9553440) in 2021), and **Semi-Supervised Learning** (see our [TGRS paper](https://hal.archives-ouvertes.fr/hal-03379500)).

\[ [EO-JEM preprint](https://hal.archives-ouvertes.fr/hal-03379500) / [EO-JEM in TGRS](https://ieeexplore.ieee.org/document/9606737) \]

## Deep Interactive + Active Learning

![image-left]({{ site.url }}{{ site.baseurl }}/images/gaston-lenczner-dial.jpg){: .align-left} 

In [Gaston Lenczner](https://gaslen.github.io/)'s PhD, we design interactive deep neural networks to foster user/algorithm collaboration. In the context of semantic segmentation  of remote sensing images, we target several use-cases including **online correction** of semantic maps (and model!) obtained by CNNs, **domain adaptation** to new locations (see our [ISPRS'2020](https://www.isprs-ann-photogramm-remote-sens-spatial-inf-sci.net/V-2-2020/877/2020/isprs-annals-V-2-2020-877-2020.pdf) and [MACLEAN 2021](http://ceur-ws.org/Vol-2766/paper1.pdf)), and **transfer learning** to add interactively new target classes to an existing model (see our [IGARSS2022 paper]()). To this end, we combine acceleration tricks and active learning to make deep networks learn continuously and efficiently from user inputs. This work is a collaboration with [Guy Le Besnerais](https://scholar.google.com/citations?user=r8V306wAAAAJ&hl=en), [Adrien Chan-Hon-Tong](https://www.onera.fr/en/staff/adrien-chan-hon-tong) (both from [ONERA](https://www.onera.fr/)) and Nicola Luminari ([Alteia](https://alteia.com/))

\[ [DISIR @ ISPRS 2020](https://www.isprs-ann-photogramm-remote-sens-spatial-inf-sci.net/V-2-2020/877/2020/isprs-annals-V-2-2020-877-2020.pdf) / [DISIR code](https://github.com/delair-ai/DISIR) / [DISCA @ ECMLPKDD/MacLean 2021 (Best student paper award!) ](http://ceur-ws.org/Vol-2766/paper1.pdf) / [DISCA Code](https://github.com/delair-ai/DISCA) / [DIAL arxiv](https://arxiv.org/abs/2201.01047) / [Transfer learning arxiv](https://arxiv.org/abs/2201.01029) \]



---

Older projects can be found [here](finished)
