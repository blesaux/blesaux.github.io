---
layout: single
title: "Projects"
permalink: /projects/finished
author_profile: true
---

{% include base_path %}

I was previously involved in these projects (now finished, or which evolve in a [new one](../projects)):


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

## AerialMTL: Multi-Task Learning for Height and Semantics prediction from bird's view

![image-left]({{ site.url }}{{ site.baseurl }}/images/marcela-carvalho-aerial-MTL-net-icon.jpg){: .align-left} 

Thanks to statistical modelling, it is now possible to build elevation or height models from a single aerial image, without the need for stereo! With [Marcela Carvalho](https://marcelampc.github.io/) we proposed to leverage **multi-task learning** to build stronger representations, by learning classes of interest along with the relative height. Indeed, similar classes of urban objects are likely to have similar heights, which brings consistence to the model. We published our results in a [paper in GRSL](https://hal-univ-paris.archives-ouvertes.fr/UNIV-PARIS5/hal-02386074/) and published the [AerialMTL code](https://github.com/marcelampc/aerial_mtl).

\[ [paper in Geosci. Rem. Sens. Lett.](https://doi.org/10.1109/LGRS.2019.2947783) / [preprint](https://hal-univ-paris.archives-ouvertes.fr/UNIV-PARIS5/hal-02386074/) / [AerialMTL github](https://github.com/marcelampc/aerial_mtl) [Code description]({{ site.url }}{{ site.baseurl }}/code) \]

## Deep Learning for Hyperspectral data: DeepHyperX and HyperGANs

![image-left]({{ site.url }}{{ site.baseurl }}/images/nicolas-audebert-GANs-hyperspectral-synthesis-icon.jpg){: .align-left} 

Hyperspectral sensors offer a unique perception on the world, in which spectral information (at multiple wavelengths, or so-to-say "colors") is as important as the spatial one. With [Nicolas Audebert](https://nicolas.audebert.at/) (prime) and [Sebastien Lefevre](http://people.irisa.fr/Sebastien.Lefevre), we investigated and reviewd various types of neural network architectures, from 1D to 3D, through complex combinations of spatial-spectral ones, to process hyperspectral data for classification. It resulted in a [review in GRSM](https://arxiv.org/abs/1904.10674) and the associated [DeepHyperX toolbox](https://github.com/nshaud/DeepHyperX) with many models ready to use on most common benchmarks! We also explored the use of Generative Adversarial Networks (GANs) to (conditionally) synthetize pure spectra (or endmmbers), and also published this [IGARSS paper](https://arxiv.org/abs/1806.02583) and the [HyperGANs toolbox](https://github.com/nshaud/HyperGANs): GANs for hyperspectral.

\[ [Deep Learning for Hyperspectral Classification]() / [DeepHyperX toolbox](https://github.com/nshaud/DeepHyperX) / [GANs for hyperspectral paper](https://arxiv.org/abs/1806.02583) / [HyperGANs toolbox](https://github.com/nshaud/HyperGANs) \]


## D^3 Net: Depth Estimation from a Single Image with Deep Depth from Defocus	 

![image-left]({{ site.url }}{{ site.baseurl }}/images/D3Net_arch_no_text-icon.jpg){: .align-left}

Turning 2D images into depth is now possible with a monocular camera, without neither stereo nor active sensor. With [Marcela Carvalho](http://mcarvalho.ml/) and Pauline Trouvé, we designed a dense network for depth estimation from a single image. We investigate how to model the right loss for such a network, and how blur from defocus can help us predict better estimates. This network ranks among the top ones of the
state of the art on the [NUYv2](https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html) dataset while being simpler to train in a single phase than most competitors.

\[ [ICIP'18 paper](http://mcarvalho.ml/material/docs/2018/regression_losses_icip_2018.pdf) / [ECCV/W'18 paper](https://arxiv.org/pdf/1809.01567.pdf) / [video](https://www.youtube.com/watch?v=Zx7k5-xc-BE) / [code]({{ site.url }}{{ site.baseurl }}/code) \]

## Joint Use of EO Data and Cartography 	 

![image-left]({{ site.url }}{{ site.baseurl }}/images/cvpr17-fusenet_osm-icon.jpg){: .align-left}

Cartography and especially crowd-sourced geographic information like [OpenStreetMap](https://www.openstreetmap.org/) is a great way to drive a neural network towards a correct classification. With Nicolas Audebert and Sébastien Lefèvre, we built fusion networks able handle efficiently this new input.

The SpaceNet Challenge round 2 winner is using a similar solution: see his [blog post which mentions our paper](http://i.ho.lc/winning-solution-for-the-spacenet-challenge-joint-learning-with-openstreetmap.html). OSM as input is promising !

\[ [CVPR'17/EarthVision paper](https://openaccess.thecvf.com/content_cvpr_2017_workshops/w18/html/Audebert_Joint_Learning_From_CVPR_2017_paper.html) / [arxiv](https://arxiv.org/abs/1705.06057) \]

## SnapNet: 3D Semantic Labeling 	 

![image-left]({{ site.url }}{{ site.baseurl }}/images/snapnet_semantic3d-icon.png){: .align-left}

As 3D sensors become ubiquitous, recognizing stuff and things in 3D data is essential. So, we developed SnapNet, a multi-view conv net for semantic labeling of unstructured 3D point clouds. During more than one year, it led the [semantic3D leaderboard](http://semantic3d.net/view_results.php?chl=1) for 3D urban mapping, and still is among the top ones. The paper was presented at [EuroGraphics](http://www.eurographics2017.fr/)/[3DOR 2017](http://liris.cnrs.fr/eg3dor2017/) and has now been published in Computer and Graphics. The [code](https://github.com/aboulch/snapnet) is also available for playing with your own data.

\[ [paper](https://blesaux.github.io/files/2017-11-10-aboulch-snapnet-CAG17.pdf) / [code](https://github.com/aboulch/snapnet) \]


## Object Detection in Remote Sensing 	 

![image-left]({{ site.url }}{{ site.baseurl }}/images/OBIA_OSM_Potsdam_3-icon.jpg){: .align-left}

With the accuracy of deep conv nets for pixelwise labeling, it is now possible to build powerful object detectors for aerial imagery. We proposed an approach to detect and segment vehicles, and then recognize their type. Our work was awarded the award for the best contribution to the [ISPRS 2D semantic labeling benchmark](http://www2.isprs.org/vaihingen-2d-semantic-labeling-contest.html) at GeoBIA'16.

\[ [Segment-before-detect](http://www.mdpi.com/2072-4292/9/4/368/pdf) paper\]


## SnapNet-R: Object Recognition for Robotics 	 

![image-left]({{ site.url }}{{ site.baseurl }}/images/wallE-recog-3D-icon.jpg){: .align-left}

In the context of robotic exploration (using micro-drones or ground robots), we aim at developing efficient object detectors and trackers that are able to adapt to a new environment. We explore how multimodal RGB-D data offers reliable and complementary ways of sensing in challenging conditions. [Joris Guerry](http://jorisguerry.fr/) has developped multimodal networks that gets high detection rates for [people detection](https://hal.archives-ouvertes.fr/hal-01628762/document) and released the [ONERA.ROOM](http://jorisguerry.fr/ONERA.ROOM/) dataset. We also proposed the SnapNet-R multi-view network for 3D-consistent data augmentation: it gets top state-of-the-art results on [NYUv2](https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html) and [Sun RGB-D](http://rgbd.cs.princeton.edu/) datasets for robotic semantic labeling.

\[ [ONERA.ROOM](http://jorisguerry.fr/ONERA.ROOM/) / [video](https://youtu.be/jEHyG2BSnGc) / [ECMR paper about people detection](https://hal.archives-ouvertes.fr/hal-01628762/document) / [ICCV/3DRMS paper about robotic semantic labeling with SnapNet-R](http://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w13/Guerry_SnapNet-R_Consistent_3D_ICCV_2017_paper.pdf) \]


## Search-and-Rescue with 3D captured from UAVs 	 

![image-left]({{ site.url }}{{ site.baseurl }}/images/lyon_inachus_damage-icon.png){: .align-left}

We are designing classifiers for 3D data captured using Lidar sensors or photogrammetry. In the [FP7 Inachus Project](http://www.inachus.eu/), we build tools for urban Search and Rescue after natural or industrial disasters: semantic maps (including safe roads and risk maps) or analysis of building damages (as shown in the image on the left: intact/blue to debris/purple). They are based on SnapNet, our multi-view convolutional net for 3D point-cloud semantic labeling.

\[  [code](https://github.com/aboulch/snapnet) / [video](https://youtu.be/xT4VrtCu8Po) \]


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
