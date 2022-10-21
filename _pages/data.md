---
layout: single
title: "Data"
permalink: /data/
author_profile: true
---

{% include base_path %}

Since machine learning algorithms are hungry for data to process, I contributed to build up various datasets. Some are listed below, other will be added soon.

## \[2022\] 2022 Data Fusion Contest: Semi-supervised Learning for Land Cover Classification

![image-left]({{ site.url }}{{ site.baseurl }}/images/DFC2022-IADF-header-sm.jpeg){: .align-left}

With Javiera Castillo-Navarro, Ronny Haensch and others, we held a competition for semi-supervised learning in Earth observation based on MiniFrance data, in the frame of the IEEE GRSS Data Fusion Contests: [the DFC2022](https://www.grss-ieee.org/community/technical-committees/2022-ieee-grss-data-fusion-contest-semi-supervised-learning-for-land-cover-classification/). Along with VHR EO imagery and landcover classes, we added digital elevation models to the new [MiniFrance-DFC22 data](https://ieee-dataport.org/competitions/data-fusion-contest-2022-dfc2022). Full description in the [GRSM Paper announcement](https://ieeexplore.ieee.org/document/9764835).

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

