---
layout: single
title: "Projects"
permalink: /projects/finished
author_profile: true
---

{% include base_path %}

I was previously involved in these projects (now finished, or which evolve in a [new one](../projects)):


## UAV Object Detection and Recognition

![image-left]({{ site.url }}{{ site.baseurl }}/images/new-workflow2-en-icon.jpg){: .align-left}

With Martial Sanfourche, we designed detectors of object of interest in images obtained from airborne sensors (UAV and planes), using a mix of geometric-template matching and learning-based classifiers. A typical use-case is a Search-and-Rescue mission in an urban environment, which objectives like cartography, obstacle avoidance or people and vehicle detection \[[video](http://www.youtube.com/watch?v=OTxaLcouOHE)\]. This research was carried on in the [FP7 Darius](http://www.darius-fp7.eu/) and Azur projects.

We presented our work on [UAV-based 3D modelling and event localization \[video\]](http://www.youtube.com/watch?v=JyHaeBkvKTQ) at the 2nd field trial of the FP7 Darius project which simulated an Urban (Earthquake) SaR Demonstration.


\[ [IROS'13 paper](../files/bls-iros2013-semantic-map.pdf) / [video #1](http://www.youtube.com/watch?v=OTxaLcouOHE) /  [video #2](http://www.youtube.com/watch?v=JyHaeBkvKTQ) \]




## Car Detection in Aerial Images

![image-left]({{ site.url }}{{ site.baseurl }}/images/gretsi15-car-detection-icon.jpg){: .align-left}

With [Hicham Randrianarivo](https://scholar.google.fr/citations?user=g5MloHAAAAAJ&hl=en) and [Marin Ferecatu](http://cedric.cnam.fr/~ferecatm/), we built powerful and fast detectors able to retrieve cars in aerial images. Our Discriminatively-trained model mixture (DtMM) was able to encode the various orientations and appearances of the cars for retrieval in higly-complex urban environments. It relied on a HOG encoding for description and a hard-negative search ofr training of linear classifiers

\[[Paper at BIDS'15](http://ceospacetech.pub.ro/images/IIM_2015_paper_8.pdf)\]

## Interactive Learning

![image-left]({{ site.url }}{{ site.baseurl }}/images/approach-dsgn-landscape2-icon.jpg){: .align-left}

Over the years, I worked on developping various methods for interactive and user-friendly design of classifiers and detectors, typically non-parametric methods like boosting and support-vector machines. The main application we investigated in the DGA-funded project Efusion was online learning of patterns of interest (objects or changes) in aerial and satellite images.

\[See [ICPR'2014 paper](../files/lesaux-icpr14.pdf) for a synthesis ].
	
## Deformable Part Models in Remote Sensing

![image-left]({{ site.url }}{{ site.baseurl }}/images/igarss14-dpm-icon.jpg){: .align-left}

With Hicham Randrianarivo, we adapted Felzenswalb's infamous Deformable Part Models to object detection in aerial images. First we shown they could be used for man-made structures in difficult urban environments \[cf. [paper at IGARSS 2013](../files/randrianarivo-dpm-igarss13.pdf)\] and then pushed them for fusion of multi-resolution, multimodal optical and hyperspectral imagery \[cf. [paper at IGARSS'14](../files/randrianarivo-multimodal-dpm-igarss14.pdf)\].

## Tomography

![image-left]({{ site.url }}{{ site.baseurl }}/images/cell3D-icon.jpg){: .align-left}

I was once interested in 3D reconstruction in tomographic imaging. The new confocal microscope we worked with was deplyed at [Institut Pasteur](https://www.pasteur.fr/en) in [Spencer Shorte](https://research.pasteur.fr/fr/member/spencer-shorte/)'s team and made possible the observation of non-adherent living cells. We used bayesian inference, data fusion and deconvolution to produce 3D volumic images of these living cells. This work was achieved in the [FP6 Automation project](http://b.chalmond.free.fr/prix/ADV_ENAutomation.pdf), with [Bernard Chalmond](http://b.chalmond.free.fr/), Jiaping Wang and [Alain Trouvé](https://atrouve.perso.math.cnrs.fr/) from the Applied Mathematics Lab of the ENS Cachan.

\[ [Paper](../files/lesaux-3Dconfocal-tomo-JMicroscopy2009.pdf) / [<span style="color:orange;">2005 CNISF/L'usine nouvelle Science Award</span>](http://b.chalmond.free.fr/prix/Les_laureats_2005.htm) \]

## Image Content Recognition

![image-left]({{ site.url }}{{ site.baseurl }}/images/image-tagging-BOW-country-icon.jpg){: .align-left}

My postdoctoral project was carried out at the [University of Bern](http://www.unibe.ch/index_eng.html) with [Horst](http://www.fki.inf.unibe.ch/staff/prof.-dr.-horst-bunke) [Bunke](https://scholar.google.com/citations?user=Lksqw0EAAAAJ) and the [CNR di Pisa](http://www.isti.cnr.it/) with [Giuseppe](http://nemis.isti.cnr.it/person/giuseppe-amato) [Amato](https://scholar.google.com/citations?user=dXcskhIAAAAJ&hl=en), as a member of the [ERCIM fellowship program](https://fellowship.ercim.eu/). I have designed predictors that can learn how to recognize scenes, like particular landscapes, sport pictures, images with people. Techniques include feature selection, kernel methods, graph matching and bayesian combination of classifiers. This was used to generate automatic annotation of multimedia documents and improve search facilities in digital libraries.

\[[A popularization article in ERCIM news](https://www.ercim.eu/publication/Ercim_News/enw58/le_saux.html)\]

## Image and Video Indexing

![image-left]({{ site.url }}{{ site.baseurl }}/images/tf1-featurespace-icon.jpg){: .align-left}

I did my PhD at [INRIA](https://www.inria.fr/en/)/[Imedia research group](https://www.inria.fr/en/teams/imedia), which is interested on content-based image retrieval. I worked on techniques of supervised and unsupervised classification to find and manage categories of visually similar images. I have developed an original algorithm for clustering : ARC (Adaptive Robust Competition).

\[ [ICPR'02 paper](../files/lesaux-icpr02.pdf) / [web version](http://blesaux.free.fr/research/research.html) \]

---

For years since the time of my PhD and my then perl-generated pure html homepage, I used to include a link to these [nice kittens who play music on the beach](http://www.rathergood.com/kittens/). Years after, this link is still up. Internet is awesome. Enjoy.
