---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

My current projects include:

## Semantic Surfaces for 3D Data

![image-left]({{ site.url }}{{ site.baseurl }}/images/semantic-surfaces-icon.png){: .align-left} 

With [Mathilde Letard](https://www.mletard.com/) from [CNRS in Rennes](https://letg.cnrs.fr/) and [Peter Naylor](https://github.com/PeterJackNaylor) from [ESA](https://philab.esa.int/) we explore new ways to learn informative representations from 3D Data using Implicit Neural Representations. It results in surfaces with semantic meaning (ground, top of canopy, etc...) which can be used for completion, super-resolution, or continuous 3D modelling. 

\[ \]

## Foundation Models for EO: PhilEO and DOFA

![image-left]({{ site.url }}{{ site.baseurl }}/images/phileo-overview-icon.png){: .align-left} 

Foundation models, that is AI models pre-trained at very large scale on massive data, have the power to revolutionise the way we use machine learning, by capturing extensive information from unlabelled data and specialising the pre-trained models on few data for specific tasks (making it parsimonious in labelled data). With the [PhilEO](https://phileo-bench.github.io/) team at [ESA](https://www.esa.int/)/[Φ-lab](https://philab.esa.int/) ([Casper Fibaek](https://github.com/casperfibaek), [Nikolaos Dionelis](https://www.linkedin.com/in/nikolaos-dionelis-60688279/), Luke Camilleri, Andreas Luyts) we proposed the [PhilEO Bench](https://phileo-bench.github.io/) to assess the capacity of emerging geospatial FMs on a benchmark of diverse tasks. We also propose the PhilEO Foundation Model and PhilEO precursor-FMs, trained at scale on massive Sentinel 2 data: PhilEO-FM is trained with geo-awareness to be more capable. PhilEO is presented at [EGU 2024](https://meetingorganizer.copernicus.org/EGU24/EGU24-17934.html) and [IGARSS 2024](https://arxiv.org/abs/2402.16147). I also collaborated with [Zhitong Xiong](https://www.asg.ed.tum.de/en/sipeo/team/dr-zhitong-xiong/) and [Xiaoxiang Zhu](https://www.professoren.tum.de/en/zhu-xiaoxiang) at [TU Munich](https://www.asg.ed.tum.de/en/sipeo/home/) who develop sensor-agnostic FM named DOFA (Dynamic One-For-All foundation model), a [Neural Plasticity-Inspired Foundation Model for Observing the Earth Crossing Modalities](https://arxiv.org/abs/2403.15356).

\[ [PhilEO Bench project](https://phileo-bench.github.io/) / [PhilEO Foundation Model]() / [PhilEO Bench on arxiv](https://arxiv.org/abs/2402.16147) / [HuggingFace community)](https://huggingface.co/PhilEO-community) / [DOFA project](https://github.com/zhu-xlab/DOFA) / [DOFA arxiv](https://arxiv.org/abs/2403.15356) \]

## Quantum Generative AI: QGANs and Quantum Diffusion Models

![image-left]({{ site.url }}{{ site.baseurl }}/images/QGAN-continuous-SYC.png){: .align-left} 

Quantum neural networks has shown interesting properties to learn faster from fewer training samples, hinting to a _different_ generalisation capacity than standard networks. We explore this potential in two works. In [Su-Yeong Chang](https://www.linkedin.com/in/su-yeon-chang-5b48a3182)'s PhD, co-supervised with [Michele Grossi](https://www.linkedin.com/in/michele-grossi-42157486/) and [Sofia Vallecorsa](https://openlab.cern/index.php/about/our-people/sofia-vallecorsa) at CERN, we build Quantum Generative Adversarial Networks (*Quantum GANs*) with continuous output generation, which allow us to generate an arbitrary number of images similar to a given dataset. With [Francesca di Falco](https://phd.uniroma1.it/web/FRANCESCA-DE-FALCO_nP1844068_IT.aspx), [Andrea Ceschini](https://phd.uniroma1.it/web/ANDREA-CESCHINI_nP1870857_IT.aspx) and [Massimo Panella](https://massimopanella.site.uniroma1.it/) from La Sapienza University and [Alessandro Sebastianelli](https://alessandrosebastianelli.github.io/) from ESA/Φ-lab, we design two variants of hybrid quantum diffusion models: embedding of quantum layers in standard diffusion models, and latent quantum diffusion models, with surprisingly good performances given the size of the models.

\[ [Quantum GANs (to appear)]() / [Hybrid Quantum Diifusion Models](https://arxiv.org/abs/2402.16147) / [Latent Quantum Diffusion Models (to appear)]() \]

## AI-based Forecast of Solar Irradiance for Renewable Energy
![image-left]({{ site.url }}{{ site.baseurl }}/images/solar-AI-forecast-icon.png){: .align-left} 

With [Alessandro Sebastianelli](https://alessandrosebastianelli.github.io/), [Federico Serva](https://fserva.github.io/) and [Quentin Paletta](https://quentinpaletta.github.io/) from [ESA](https://www.esa.int/)/[Φ-lab](https://philab.esa.int/) on the one hand, and on the other hand [Andrea Ceschini](https://phd.uniroma1.it/web/ANDREA-CESCHINI_nP1870857_IT.aspx) and [Massimo Panella](https://massimopanella.site.uniroma1.it/) from La Sapienza University (DIET - [Department of Information Engineering](https://web.uniroma1.it/dip_diet/)), we developped and benchmarked methods for AI-based forecasting of solar irradiance from previous days and Meteosat weather data. I also collaborated with [Quentin Paletta](https://quentinpaletta.github.io/) for to improve spatial domain adaptation of AI solar forecasting models with physics-informed transfer learning.

\[ [AI Forecast of irradiance]() / [Energy Conversion and Management paper on _cross-site generalizability of vision-based solar forecasting models with physics-informed transfer learning_](https://doi.org/10.1016/j.enconman.2024.118398) \]


## Physics-aware ML for Weather Forecast
![image-left]({{ site.url }}{{ site.baseurl }}/images/weather4cast-icon.png){: .align-left} 

With [Federico Serva](https://fserva.github.io/) we investigate forecasting of weather events. In particular, we're part of the organising committee of the [Weather4Cast](https://weather4cast.net/) competition led by [Aleksandra Gruca](https://www.researchgate.net/profile/Aleksandra-Gruca) and [David Kreil](https://www.researchgate.net/profile/David-Kreil-2) at NeurIPS in 2022 and 2023, which establish a benchmark for rain prediction from spatio-temporal time-series (i.e. movies). Check the report on the 2022 edition: [Weather4cast at NeurIPS 2022: Super-Resolution Rain Movie Prediction under Spatio-temporal Shifts](https://proceedings.mlr.press/v220/gruca23a.html) in PMLR. In parallel, we developed [Super-resolved rainfall prediction with physics-aware deep learning](https://arxiv.org/abs/2310.15615) approaches for rain prediction with Stephen Moran and [Begum Demir](https://begumdemir.com/) from TU Berlin.

\[ [Weather4Cast](https://weather4cast.net/) / [Weather4cast at NeurIPS 2022](https://nips.cc/virtual/2022/competition/50099) /  [Weather4cast Paper 2022 in PMLR](https://proceedings.mlr.press/v220/gruca23a.html) /  [Weather4cast at NeurIPS 2023](https://neurips.cc/virtual/2023/competition/66592) /  [Rain prediction paper at BiDS'23](https://arxiv.org/abs/2310.15615) / \]


## Unsupervised AI for Forestry and Biomass

![image-left]({{ site.url }}{{ site.baseurl }}/images/paluba-SAR-NDVI-icon.png){: .align-left} 

With the [EO4Landscape](https://eo4landscape.natur.cuni.cz/) [group](https://eo4landscape.natur.cuni.cz/team/) of [Univerzita Karlova](https://www.natur.cuni.cz/geografie/geoinformatika-kartografie/veda-a-vyzkum/vyzkumne-tymy/vyzkumny-tym-hodnoceni-land-use-a-land-cover-z-druzicovych-dat) ([Charles University](https://cuni.cz/UKEN-1.html)) in Pragues: [Přemysl Štych](https://eo4landscape.natur.cuni.cz/premysl-stych/), Daniel Paluba, and Jan Svoboda, we investigate AI with no or low supervision to classify forests and trees. With [Daniel Paluba](https://eo4landscape.natur.cuni.cz/daniel-paluba/) (and Francesco Sarti from [ESA](https://www.esa.int/)), we developed an approach to estimate common forest index (LAI, NDVI, etc.) from SAR data (Sentinel 1) so forests can be monitored even in the presence of clouds. With [Jan Svoboda](https://eo4landscape.natur.cuni.cz/jan-svoboda/) (and [Peter Naylor](https://github.com/PeterJackNaylor) from [ESA](https://philab.esa.int/)) we worked on land cover classification refinement using [Segment-Anything](https://segment-anything.com/)-based image segmentation.

\[ [Estimating optical vegetation indices with Sentinel-1 SAR data and AutoML](https://arxiv.org/abs/2311.07537) / [Forest dataset (_to appear_)]() / [EARSEL'2024 paper on Segment-Anything for Landcover]() \]


## Visual Question & Answering (VQA) for EO data

![image-left]({{ site.url }}{{ site.baseurl }}/images/christel-chappuis-rsvqa-icon.jpg){: .align-left} 

In [Christel Chappuis](https://people.epfl.ch/christel.chappuis/?lang=en)'s PhD at [EPFL](https://www.epfl.ch/en/)/[ECEO](https://www.epfl.ch/labs/eceo/), co-supervised with [Devis Tuia](https://sites.google.com/site/devistuia/) ([EPFL](https://www.epfl.ch/labs/eceo)) and [Sylvain Lobry](https://www.sylvainlobry.com/) ([Univ. of Paris](https://u-paris.fr/en/)), we investigate remote sensing visual question & answering (RSVQA). _How to interact easily with Earth observation and geospatial data archives, using natural language and no computer expertise?_ This is key for empowering people with EO capacities! We explored image-text embedding for RSVQA ([ECML-PKDD Workshop paper](https://arxiv.org/abs/2109.11848)) and now are moving to advanced Natural Language Processing (NLP) techniques to address times-series of environmental data.

\[ [image-text embedding paper](https://arxiv.org/abs/2109.11848) and [video](https://tube.switch.ch/videos/uvBPd4XtZ8) \]

## Quantum Computing for Earth Observation

![image-left]({{ site.url }}{{ site.baseurl }}/images/qc4eo-icon.png){: .align-left} 

While at [ESA](https://www.esa.int/)/[Φ-lab](https://philab.esa.int/), I supervised the **Quantum Computing for Earth Observation (QC4EO)** initiative to bring the power of Quantum Computing to EO. The action was three-fold. 1, we launched research projects on scientific questions to assess the potential of emerging techonologies such as Quantum Machine Learning with [CERN](https://openlab.cern/) [announce](https://philab.esa.int/flagship-programmes/qc4eo/), [Forschungszentrum Jülich](https://www.fz-juelich.de/en), [Jagiellonian University](https://en.uj.edu.pl/)/[Quantum Cosmos Lab](https://quantumcosmos.org/), [Nicolaus Copernicus Astronomical Center of the Polish Academy of Sciences ](https://camk.edu.pl/en/) etc. 2, we launched two large-scale studies with European groups of Industry and Academic experts, led by [Forschungszentrum Jülich](https://www.fz-juelich.de/en) and the [German Aerospace Center (DLR)](https://www.dlr.de/en), to identify EO use-cases for QC and define a roadmap for the next 15 years. 3, we built from scratch a QCxEO community with experts from both fields to stimulate today's research and prepare tomorrow's workforce; it included workshop with [ELLIS](https://ellis.eu/) ([ellis page](https://ellis.eu/events/ellis-esa-workshop-on-quantum-computing-for-huge-data-analysis-simulation-and-potential-applications-to-earth-observation) / [workshop page](https://ellisqphml.github.io/ellisphilab2021)) or [Forschungszentrum Jülich](https://www.fz-juelich.de/en): the [High Performance and Innovative Computing for EO workshop](https://indico3-jsc.fz-juelich.de/event/135/), participation to summer schools (IEEE, CINECA, EQAI) and multiple industry or academia events (TERATEC-Thales, QTML, etc.), co-organisation of the ESA Quantum Conference in [2021](https://atpi.eventsair.com/5th-quantum-technology-conference/) and [2023](https://nikal.eventsair.com/6th-quantum-technology-conference/), and edition of special issues in scientific journals ([JSTARS special issue on quantum resources for EO](https://www.grss-ieee.org/events/special-issue-on-quantum-computing-for-earth-observation/)).

\[ [All outputs of Quantum Computing for EO study](https://eo4society.esa.int/projects/qc4eo-study/) / [All outputs of Quantum Advantage for EO study](https://eo4society.esa.int/projects/qa4eo-study/) /  HPIC workshop [slides](https://eo4society.esa.int/projects/qc4eo-study) / [report](https://eo4society.esa.int/wp-content/uploads/2024/02/ESA-High-Performance-and-Innovative-Computing-WS-Report.pdf) / [overall presentation at QTML'2023](https://indico.cern.ch/event/1288979/contributions/5677697/attachments/2757215/4800831/QTML%20ESA%20at%20Industry%20Panel.pdf) \]


---

Older projects can be found [here](finished)
