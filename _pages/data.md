---
layout: single
title: "Data"
permalink: /data/
author_profile: true
---

{% include base_path %}

Since machine learning algorithms are hungry for data to process, I contributed to build up various datasets. Some are listed below, other will be added soon.

## \[2025\] IceCloudNet: 3D reconstruction of clouds from 2D SEVIRI images 

![image-left]({{ site.url }}{{ site.baseurl }}/images/icecloudnet.gif){: .align-left}{: width="40%"}

[*IceCloudNet: 3D Reconstruction of Cloud Ice from Meteosat SEVIRI*](https://www.wdc-climate.de/ui/entry?acronym=IceCloudNet_3Drecon) is now published in the 𝘈𝘳𝘵𝘪𝘧𝘪𝘤𝘪𝘢𝘭 𝘐𝘯𝘵𝘦𝘭𝘭𝘪𝘨𝘦𝘯𝘤𝘦 𝘧𝘰𝘳 𝘵𝘩𝘦 𝘌𝘢𝘳𝘵𝘩 𝘚𝘺𝘴𝘵𝘦𝘮𝘴 journal of the American Meteorological Society. [5 years of cloud data](https://www.wdc-climate.de/ui/entry?acronym=IceCloudNet_3Drecon) and [code to produce more](https://github.com/tabularaza27/ice_cloud_net) are now public, enabling study of **𝐜𝐥𝐨𝐮𝐝 𝐟𝐨𝐫𝐦𝐚𝐭𝐢𝐨𝐧 𝐚𝐧𝐝 𝐝𝐞𝐯𝐞𝐥𝐨𝐩𝐦𝐞𝐧𝐭** at very large scale as well as validation of **𝐡𝐢𝐠𝐡-𝐫𝐞𝐬𝐨𝐥𝐮𝐭𝐢𝐨𝐧 𝐰𝐞𝐚𝐭𝐡𝐞𝐫 𝐚𝐧𝐝 𝐜𝐥𝐢𝐦𝐚𝐭𝐞 𝐦𝐨𝐝𝐞𝐥 𝐬𝐢𝐦𝐮𝐥𝐚𝐭𝐢𝐨𝐧𝐬**. In brief, IceCloudNet:

👉 reconstructs in **3D Clouds**' key parameters such as **ice water** content and **ice crystal** number concentration.

👉 transforms globally-available **2D** images from Meteosat MSG instrument **SEVIRI** into large-scale **3D** scans as obtained by LiDARs on-board the **CALIPSO** and CloudSat missions.

👉 demonstrates how GenerativeAI can **extend the life** of satellites, **expand** the covered area, and empower scientists with new tools to study natural phenomena.

This was an effort led by [Kai Jeggle](https://scholar.google.com/citations?user=5_fiN-sAAAAJ) with [David Neubauer](https://www.linkedin.com/in/david-neubauer-phd) and [Ulrike Lohmann](https://iac.ethz.ch/people-iac/person-detail.html?persid=121007) at [ETH Zurich](https://ethz.ch/en.html) and [Federico Serva](https://iris.cnr.it/cris/rp/rp10367), [Mikolaj Czerkawski](https://mikonvergence.github.io/) and myself at [ESA Φ-lab
](https://philab.esa.int/)

## \[2022\] 2022 Data Fusion Contest: Semi-supervised Learning for Land Cover Classification

![image-left]({{ site.url }}{{ site.baseurl }}/images/DFC2022-IADF-header-sm.jpeg){: .align-left}

With [Javiera Castillo-Navarro](https://javi-castillo.github.io/), [Ronny Haensch](http://www.rhaensch.de/) and others, we held a competition for semi-supervised learning in Earth observation based on MiniFrance data, in the frame of the IEEE GRSS Data Fusion Contests: [the DFC2022](https://www.grss-ieee.org/community/technical-committees/2022-ieee-grss-data-fusion-contest-semi-supervised-learning-for-land-cover-classification/). Along with VHR EO imagery and landcover classes, we added digital elevation models to the new [MiniFrance-DFC22 data](https://ieee-dataport.org/competitions/data-fusion-contest-2022-dfc2022). Full description in the [GRSM Paper announcement](https://ieeexplore.ieee.org/document/9764835).

## \[2022\] Hyperview Challenge: Estimating Soil Parameters from Hyperspectral Images

![image-left]({{ site.url }}{{ site.baseurl }}/images/hyperview-icon.png){: .align-left}

With [Jakub Nalepa](https://www.researchgate.net/profile/Jakub-Nalepa-2), [Nicolas Longépé](), and colleagues from New Space company [KP Labs](https://kplabs.space/) and [ESA](https://www.esa.int/) organised the [HyperView](https://platform.ai4eo.eu/seeing-beyond-the-visible-permanent) challenge for geology and agriculture from space, leveraging hyperspectral imagery (check the [video](https://youtu.be/UeBbkfLJe40)). Hyperview _"Seeing beyond the visible"_  was powered by the [ai4eo.eu platform](https://ai4eo.eu/challenge/hyperview-challenge/) and held as a Grand Challenge at [ICIP 2022](https://2022.ieeeicip.org/challenges/) ([Hyperview description in the ICIP paper](https://ieeexplore.ieee.org/document/9897443)).

{::options parse_block_html="true" /}
<details>
You are free to use and/or refer to the HYPERVIEW dataset in your own research (non-commercial use): [hyperview can be found here](https://platform.ai4eo.eu/seeing-beyond-the-visible-permanent/data) and the (incomplete) [PapersWithCode entry is here](https://paperswithcode.com/dataset/hyperview). If using this dataset, please cite: **The Hyperview Challenge: Estimating Soil Parameters from Hyperspectral Images** _Nalepa et al._ IEEE ICIP Bordeaux, France, October 2022

```
@INPROCEEDINGS{9897443,
  author={Nalepa, Jakub and {Le Saux}, Bertrand and {Longépé}, Nicolas and Tulczyjew, Lukasz and Myller, Michal and Kawulok, Michal and Smykala, Krzysztof and Gumiela, Michal},
  booktitle={2022 IEEE International Conference on Image Processing (ICIP)},
  title={The Hyperview Challenge: Estimating Soil Parameters from Hyperspectral Images},
  year={2022},
  pages={4268-4272},
  doi={10.1109/ICIP46576.2022.9897443}
}
```
</details>

{::options parse_block_html="false" /}

## \[2020\] MiniFrance Dataset

With Javiera Castillo-Navarro et al., we released the first benchmark for semi-supervised learning in Earth observation: [MiniFrance](https://ieee-dataport.org/open-access/minifrance).

## \[2020\] SEN12-FLOOD Dataset

![image-left]({{ site.url }}{{ site.baseurl }}/images/sen12floods-icon.png){: .align-left}

With Clément Rambour et al., we released [SEN12-FLOOD](https://ieee-dataport.org/open-access/sen12-flood-sar-and-multispectral-dataset-flood-detection), a SAR-Multispectral dataset for classification of flood events in image time-series. And the dataset is also available on [Radiant Earth](https://www.radiant.earth/) platform: [MLHub.earth](https://mlhub.earth/data/sen12floods)

## \[2019\] High-Res. Semantic Change Dataset (HRSCD) 

![image-left]({{ site.url }}{{ site.baseurl }}/images/HRSCD-icon.png){: .align-left}

With [Rodrigo Daudt](https://rcdaudt.github.io) et a., we also released HRSCD, a large-scale dataset for semantic change detection at high-resolution (0.5m/pixel). \[ [HRSCD website @ Rodrigo](https://rcdaudt.github.io/hrscd/) / [HRSCD website @ DataPort](https://ieee-dataport.org/open-access/hrscd-high-resolution-semantic-change-detection-dataset) \].

## \[2019\] Data Fusion Contest 2019 (DFC2019)

![image-left]({{ site.url }}{{ site.baseurl }}/images/dfc19-icon.png){: .align-left}

The [DFC2019](http://www.grss-ieee.org/community/technical-committees/data-fusion/2019-ieee-grss-data-fusion-contest-data/) organised by IADF TC (Myself, Naoto Yokoya and Ronny Hänsch) and Johns Hopkins University (Myron Brown) was a benchmark about Large-Scale Semantic 3D Reconstruction, and involved 3D reconstruction, 3D prediction, and semantic segmentation in 2D and 3D. \[ [DFC2019 @ IEEE GRSS](http://www.grss-ieee.org/community/technical-committees/data-fusion/2019-ieee-grss-data-fusion-contest-data/) / [DFC2019 @ DataPort](https://ieee-dataport.org/open-access/data-fusion-contest-2019-dfc2019) \]

## \[2018\] Onera Satellite Change Detection (OSCD) Dataset  [![DOI]({{ site.url }}{{ site.baseurl }}/images/doi-OSCD.png)](http://dx.doi.org/10.21227/asqe-7s69)

![image-left]({{ site.url }}{{ site.baseurl }}/images/beirut-OSCD-icon.png){: .align-left}

[Onera Satellite Change Detection (OSCD) Dataset](https://rcdaudt.github.io/oscd/)

With [Rodrigo Daudt](https://rcdaudt.github.io), we released the first dataset for training deep learning models for pixelwise change detection over Sentinel-2 data. It comprises 24 registered pairs of multispectral images from 2015 and 2018, all over the world. \[ [OSCD paper @ IGARSS'18]() / [Prime OSCD website @ Rodrigo](https://rcdaudt.github.io/oscd/) / [Alternate OSCD website @ DataPort](https://ieee-dataport.org/open-access/oscd-onera-satellite-change-detection) / Related: [CNNs for Change Detection](https://github.com/rcdaudt/fully_convolutional_change_detection) / [Evaluation @ DASE](http://dase.grss-ieee.org/index.php) \]

{::options parse_block_html="true" /}
<details>
This dataset contains modified Copernicus data from 2015-2018. Original Copernicus Sentinel Data available from the European Space Agency ([https://sentinel.esa.int](https://sentinel.esa.int)). Change label maps are released under [Creative-Commons BY-NC-SA](https://creativecommons.org/licenses/by/4.0/). If using this dataset, please cite: **Urban Change Detection for Multispectral Earth Observation Using Convolutional Neural Networks** _R. Caye Daudt, B. Le Saux, A. Boulch, and Y. Gousseau_ IEEE IGARSS Valencia, Spain, July 2018

```
@inproceedings{daudt2018urban,
  author = { {Caye Daudt}, R. and {Le Saux}, B. and Boulch, A. and Gousseau, Y.},
  title = {Urban Change Detection for Multispectral Earth Observation Using Convolutional Neural Networks},
  booktitle = {IEEE Int. Geoscience and Remote Sensing Symposium (IGARSS)},
  address =  {Valencia, Spain},
  month = {July},
  year = {2018},
}
```
</details>

{::options parse_block_html="false" /}

## \[2018\] Data Fusion Contest 2018 (DFC2018)

![image-left]({{ site.url }}{{ site.baseurl }}/images/dfc18-icon.png){: .align-left}

The [DFC2018](http://www.classic.grss-ieee.org/community/technical-committees/data-fusion/2018-ieee-grss-data-fusion-contest/) organised by IADF TC (Myself, Naoto Yokoya and Ronny Hänsch) and Houston University (Saurabh Prasad) was a benchmark about urban land use and land cover classification (or semantic segmentation). It used multispectral LiDAR point cloud data (intensity rasters and digital surface models), **hyperspectral** data, and very high-resolution RGB imagery. As such, it still is a relevant becnhmark for hyperspectral classification and data fusion. \[ [DFC2018 @ IEEE GRSS](http://www.classic.grss-ieee.org/community/technical-committees/data-fusion/2018-ieee-grss-data-fusion-contest/) / [DFC2018 @ DataPort](https://ieee-dataport.org/open-access/2018-ieee-grss-data-fusion-challenge-%E2%80%93-fusion-multispectral-lidar-and-hyperspectral-data) \]


## \[2013\] Christchurch Aerial Semantic Dataset (CASD) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3566005.svg)](https://doi.org/10.5281/zenodo.3566005)


![image-left]({{ site.url }}{{ site.baseurl }}/images/christchurch-CASD-icon.jpg){: .align-left}

[Christchurch Aerial Semantic Dataset (CASD)](https://zenodo.org/record/3566005)

Hicham Randrianarivo and I annotated images from [Land Information New Zealand (LINZ)](https://www.linz.govt.nz/land/maps/linz-topographic-maps/imagery-orthophotos/christchurch-earthquake-imagery) with urban semantic classes: buildings, vehicles and vegetation. Annotations come at object level (shapefiles) and semantic maps (raster masks). All data (images and annotations) are under [License CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). \[ Report: [Cristchurch CASD]({{ site.url }}{{ site.baseurl }}/files/christchurch-CASD.pdf) / Related: [Deformable Part Models for remote sensing](http://blesaux.free.fr/papers/randrianarivo-2013-igarss-DPM.pdf) / [DtMM for Vehicle Detection]({{ site.url }}{{ site.baseurl }}/files/randrianarivo-DtMM-vehicles-IIM2015.pdf) / [Segment-before-detect paper](http://blesaux.free.fr/papers/17-RemoteSensing-Segment-before-detect-AudebertLeSauxLefevre-compressed.pdf) \]

{::options parse_block_html="true" /}
<details>
If using this dataset, please cite: **Man-made structure detection with deformable part-based models** _H. Randrianarivo, B. Le Saux, and M. Ferecatu_ IEEE IGARSS Melbourne, Australia, July 2013

```
@inproceedings{randrianarivo-13igarss-DPM,
author = {Randrianarivo, H. and {Le Saux}, B. and Ferecatu, M.},
title = {Man-made structure detection with deformable part-based models},
booktitle = {IEEE Int. Geoscience and Remote Sensing Symposium (IGARSS)},
year = {2013},
month = {July},
address = {Melbourne, Australia},
}
```
</details>

{::options parse_block_html="false" /}

