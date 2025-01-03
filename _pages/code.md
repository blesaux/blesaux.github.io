---
layout: single
title: "Code"
permalink: /code/
author_profile: true
---

{% include base_path %}

Over the years, research projects and papers lead to various code and computer tools. Here, they are made available for the sake of reproducible research and to enable you to make use of it for building new extensions.


## PhilEO-Bench: a benchmark for geospatial foundation models

![image-left]({{ site.url }}{{ site.baseurl }}/images/phileo-overview-icon.png){: .align-left}

[Project page](https://phileo-bench.github.io/) with links to [GitHub](https://github.com/ESA-PhiLab/PhilEO-Bench), [HugginFace](https://huggingface.co/PhilEO-community) and [Dataset of downsteam tasks](http://huggingface.co/datasets/ESA-philab/PhilEO-downstream).

The PhilEO-bench is a benchmark for geospatial foundation models (e.g. trained on Sneitnel 2 or HLS data) with three tasks (land cover classification, road segmentation, and building density regression) on the same massive and global dataset (400Go). Thus, this is a real game changer for really evaluating EO foundation models and their assumptions of _universality_ (everywhere on Earth) and _genericity_ (multiple tasks). In the [paper](https://arxiv.org/abs/2401.04464) ([pdf](https://arxiv.org/pdf/2401.04464)) we compare various foundation models such as Prithvi, SeCo, Satlas to our own Foundation Model: PhilEO. Weights are on the [huggin face page](https://huggingface.co/PhilEO-community)!

{::options parse_block_html="true" /}
<details>

If using this code, please cite: **PhilEO Bench: Evaluating Geo-Spatial Foundation Models** _Casper Fibaek, Luke Camilleri, Andreas Luyts, Nikolaos Dionelis, Bertrand Le Saux_ IGARSS, July 2024.

```
@inproceedings{fibaek2024-phileo-bench,
 author = { Fibaek, Casper and  Camilleri, Luke and  Luyts, Andreas and  Dionelis, Nikolaos and  {Le Saux}, Bertrand},
 title = {PhilEO Bench: Evaluating Geo-Spatial Foundation Models},
 journal={IGARSS},
 month = {July},
 year = {2024},
}
```
</details>

{::options parse_block_html="false" /}

## AerialMTL: Multi-Task Learning for Aerial Images

![image-left]({{ site.url }}{{ site.baseurl }}/images/mtl-sem-height-icon.jpg){: .align-left}

[AerialMTL code](https://github.com/marcelampc/aerial_mtl) on github

With [Marcela Carvalho](http://mcarvalho.ml/), we developped this approach for joint estimation of *3D* (Digital Height Models) and *semantics* (urban cartography) from aerial images. \[ Related:  [GRSL article](https://doi.org/10.1109/LGRS.2019.2947783) / [preprint](https://hal-descartes.archives-ouvertes.fr/hal-02386074/) / [DFC 2018 data](http://www.grss-ieee.org/community/technical-committees/data-fusion/2018-ieee-grss-data-fusion-contest/)  \]

{::options parse_block_html="true" /}
<details>

It consists in a deep network for _Multi-Task Learning_ and we've shown that each task help the other to get better results on both ISPRS Vaihingen and [IEEE GRSS Data Fusion Contest 2018](http://www.grss-ieee.org/community/technical-committees/data-fusion/2018-ieee-grss-data-fusion-contest/).

If using this code, please cite: **Multitask learning of Height and Semantics From Aerial Images** _M. Pinheiro de Carvalho, B. Le Saux, P. Trouvé-Peloux, F. Champagnat, A. Almansa_ [IEEE Geoscience and Remote Sensing Letters (GRSL)](https://doi.org/10.1109/LGRS.2019.2947783), Nov. 2019.

```
@article{carvalho-2019grsl-mtl3D,
 author = {Carvalho, Marcela and {Le Saux}, Bertrand and Trouv{\'e}-Peloux, Pauline and Champagnat, Fr{\'e}d{\'e}ric and Almansa, Andr{\`e}s},
 title = {Multitask learning of Height and Semantics From Aerial Images},
 journal={IEEE Geosci. and Remote Sensing Letters},
 month = {November},
 year = {2019},
}
```

</details>

{::options parse_block_html="false" /}


## HyperGANs: GANs for Hyperspectral Toolbox

![image-left]({{ site.url }}{{ site.baseurl }}/images/nicolas-audebert-GANs-hyperspectral-synthesis-icon.jpg){: .align-left}

[HyperGANs code](https://github.com/nshaud/HyperGANs)

The HyperGANs toolbox by [Nicolas Audebert](https://nicolas.audebert.at/) implements Generative Adversarial Network (GAN) for synthesis of realistic hyperspectral spectra (conditioned by material class / after mixing). \[Related: [GANs for hyperspectral paper](https://arxiv.org/abs/1806.02583) with [Sébastien Lefèvre](http://people.irisa.fr/Sebastien.Lefevre/)\]

{::options parse_block_html="true" /}
<details>
 It allows to generate spectra of a hyperspectral sensor which are likely with respect to the original distribution of the training example dataset. Moreover, it comes in a class-conditional flavour, which allows to synthetise realistic samples of pure material spectra. It can be easily adapted to new datasets.

If using this code, please cite: **Generative adversarial networks for realistic synthesis of hyperspectral samples** _Nicolas Audebert, Bertrand Le Saux, Sébastien Lefèvre_, Proc. IGARSS 2018. [https://arxiv.org/abs/1904.10674](https://arxiv.org/abs/1904.10674)

```
@inproceedings{audebert_generative_2018,
 title = {Generative adversarial networks for realistic synthesis of hyperspectral samples},
 booktitle = {Proc. IGARSS},
 author = {Audebert, N. and Le Saux, B. and Lefèvre, S.},
 month = {jul},
 year = {2018},
 } 
```

</details>

{::options parse_block_html="false" /}

## D3Net: An encoder-decoder FCN with dense blocks

![image-left]({{ site.url }}{{ site.baseurl }}/images/D3Net_arch_no_text-icon.jpg){: .align-left}

[D3-Net code](https://github.com/marcelampc/d3net_depth_estimation) on github

[Marcela Carvalho](http://mcarvalho.ml/)'s code for depth estimation from a single image: it ranked among the top ones of the state of the art on the [NUYv2](https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html) dataset while being simpler to train in a single phase than most competitors. \[ Related: [ICIP 2018 paper](http://mcarvalho.ml/material/docs/2018/regression_losses_icip_2018.pdf) / [ECCV/W 2018 paper](http://www.sys.info.hiroshima-cu.ac.jp/3drw2018/procs/W17-01.pdf) / [video](https://www.youtube.com/watch?v=Zx7k5-xc-BE) \]


{::options parse_block_html="true" /}
<details>

It has a fully-convolutional network architecture which incorporates the nice features of [densely connected conv nets](https://arxiv.org/abs/1608.06993) and skipping connections _a la_ [U-net](https://arxiv.org/abs/1505.04597) in an encoder-decoder net. Moreover, upsampling is simpler than [Tiramisu](https://arxiv.org/abs/1611.09326), which results in a smaller model, usable on most GPUs.

If using this code, please cite: **On Regression Losses for Deep Depth Estimation** _M. Pinheiro de Carvalho, B. Le Saux, P. Trouvé-Peloux, F. Champagnat, A. Almansa_ IEEE Int. Conf. on Image Processing ([ICIP'2018](https://2018.ieeeicip.org/)) Athens, Greece, October 2018

```
@inproceedings{carvalho-18icip-losses,
 author = {Carvalho, Marcela and {Le Saux}, Bertrand and Trouv{\'e}-Peloux, Pauline and Champagnat, Fr{\'e}d{\'e}ric and Almansa, Andr{\`e}s},
 title = {On Regression Losses for Deep Depth Estimation},
 booktitle = {IEEE Int. Conf. on Image Processing ({ICIP})},
 address = {Athens, Greece},
 year = {2018},
}

```

</details>

{::options parse_block_html="false" /}

## DeepHyperX: Deep Learning for Hyperspectral Imaging Toolbox

![image-left]({{ site.url }}{{ site.baseurl }}/images/deephyperx-icon.png){: .align-left}

[DeepHyperX code](https://gitlab.inria.fr/naudeber/DeepHyperX/)

[Nicolas Audebert](https://nicolas.audebert.at/) coded this toolbox with various machine learning / deep neural network approaches for hyperspectral imaging, in support of a review we wrote with [Sébastien Lefèvre](http://people.irisa.fr/Sebastien.Lefevre/). \[ Related: [Deep Learning for Hyperspectral review in GRSM](https://arxiv.org/abs/1904.10674) \]

{::options parse_block_html="true" /}
<details>
 It contains various models, from SVM to convolutional nets, including 1D, 2D or 3D CNNs, multi-scale or sumi-supervised. Various approaches of the State of the Art are reproduced. Various standard datasets are already included (including Indian Pines, Pavia or DFC 2018), and there is a tutorial to include our own ones. The most straightforward way to start with deep learning in hyperspectral!

If using this code, please cite: **Deep Learning for Classification of Hyperspectral Data: A Comparative Review** _Nicolas Audebert, Bertrand Le Saux, Sébastien Lefèvre_, IEEE Geoscience Remote Sensing Magazine, vol. 7 (2), 2019. [https://arxiv.org/abs/1904.10674](https://arxiv.org/abs/1904.10674)

```
@article{audebert-19grsm-deep-hyper-X,
 author = {Audebert, Nicolas and {Le Saux}, Bertrand and Lef{\`e}vre, S{\'e}bastien},
 title = {Deep Learning for Classification of Hyperspectral Data: A Comparative Review},
 journal = {IEEE Geoscience Remote Sensing Magazine},
 volume = {7},
 number = {2},
 year = {2019},
 month={June},
}
```

</details>

{::options parse_block_html="false" /}


## SnapNet: Multi-view conv net for 3D semantic labeling 	 

![image-left]({{ site.url }}{{ site.baseurl }}/images/snapnet-icon.png){: .align-left}

[SnapNet code](https://github.com/aboulch/snapnet) on github


With [Alexandre Boulch](http://www.boulch.eu/), we conceived SnapNet, a multi-view conv net for semantic labeling of unstructured 3D point clouds. During more than one year, it led the [semantic3D leaderboard](http://semantic3d.net/view_results.php?chl=1) for 3D urban mapping, and still is among the top ones. \[ Related: [CaG 2017 paper](https://blesaux.github.io/files/2017-11-10-aboulch-snapnet-CAG17.pdf) /  [ICCV/W 2017 paper](http://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w13/Guerry_SnapNet-R_Consistent_3D_ICCV_2017_paper.pdf) \]


{::options parse_block_html="true" /}
<details>
In particular, it is computationally efficient and allows to deal with large datasets in tractable times. With Joris Guerry, we developped a variant which was aplied on robotics datasets such as NYUv2 or SunRGBD with excellent classification results.

If using this code, please cite: **SnapNet: Unstructured point cloud semantic labeling using deep segmentation networks** _Alexandre Boulch, Joris Guerry, Bertrand Le Saux, Nicolas Audebert_, Computer and Graphics, 2017

```
@article{boulch-17cag-snapnet,
  title={SnapNet: 3D point cloud semantic labeling with 2D deep segmentation networks},
  author={Boulch, Alexandre and Guerry, Joris and {Le Saux}, Bertrand and Audebert, Nicolas},
  journal={Computers \& Graphics},
  year={2017},
  publisher={Elsevier}
}
```

</details>

{::options parse_block_html="false" /}




## DeepNetsForEO: Deep learning for Earth Observation 	 

![image-left]({{ site.url }}{{ site.baseurl }}/images/DeepNetForEO-icon.jpg){: .align-left}

[DeepNetsForEO code](https://github.com/nshaud/DeepNetsForEO)

With [Nicolas Audebert](https://nicolas.audebert.at/) and [Sébastien Lefèvre](http://people.irisa.fr/Sebastien.Lefevre/), we released [DeepNetsForEO](https://github.com/nshaud/DeepNetsForEO), a deep learning python software for semantic labeling of Earth Observation images. \[ Related: [ISPRS Journal of Photogrammetry 2017 paper](https://hal.archives-ouvertes.fr/hal-01636145/document) /  [ACCV 2016 paper](https://hal.archives-ouvertes.fr/hal-01360166/file/accv16_final_483.pdf) \]


{::options parse_block_html="true" /}
<details>

It is a deep neural network based on the [SegNet](https://arxiv.org/abs/1511.02680) architecture, with [pre-trained weights](http://www-obelix.irisa.fr/software/) on various public remote sensing datasets like [ISPRS Vaihingen](http://www2.isprs.org/commissions/comm3/wg4/2d-sem-label-vaihingen.html) and [ISPRS Potsdam](http://www2.isprs.org/potsdam-2d-semantic-labeling.html). The v1 (Caffe and python interface) was the first deep learning model for Earth-observation data available in the [Caffe model zoo](https://github.com/BVLC/caffe/wiki/Model-Zoo#deep-networks-for-earth-observation). The v2 is purely python with pytorch functions, and comes with a handy python notebook.

If using this code, please cite: **Beyond RGB: Very high resolution urban remote sensing with multimodal deep networks** _Nicolas Audebert, Bertrand Le Saux, Sébastien Lefèvre_, ISPRS Journal of Photogrammetry and Remote Sensing, 2018. [https://arxiv.org/abs/1711.08681](https://arxiv.org/abs/1711.08681)

```
@article{audebert_beyondRGB_2018,
title = "Beyond RGB: Very high resolution urban remote sensing with multimodal deep networks",
journal = "ISPRS Journal of Photogrammetry and Remote Sensing",
year = "2018",
issn = "0924-2716",
doi = "https://doi.org/10.1016/j.isprsjprs.2017.11.011",
author = "Audebert, Nicolas and {Le Saux}, Bertrand and Lef{\`e}vre, S{\'e}bastien",
keywords = "Deep learning, Remote sensing, Semantic mapping, Data fusion"
}

```

</details>

{::options parse_block_html="false" /}




