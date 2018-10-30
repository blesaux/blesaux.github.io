---
layout: single
title: "Code"
permalink: /code/
author_profile: true
---

{% include base_path %}

Over the years, research projects and papers lead to various code and computer tools. They are here made available for the sake of reproducible research and to enable you to make use of it for building new extensions.


## D3Net: An encoder-decoder FCN with dense blocks

![image-left]({{ site.url }}{{ site.baseurl }}/images/D3Net_arch_no_text-icon.jpg){: .align-left}

[D3-Net code](https://github.com/marcelampc/d3net_depth_estimation)

[Marcela Carvalho](http://mcarvalho.ml/) designed a fully-convolutional network architecture which incorporates the nice features of [densely connected conv nets](https://arxiv.org/abs/1608.06993) and skipping connections a la [U-net](https://arxiv.org/abs/1505.04597) in an encoder-decoder net. Moreover, upsampling is simpler than [Tiramisu](https://arxiv.org/abs/1611.09326), which results in a smaller model, usable on most GPUs.
 
It was successfully applied to depth estimation from a single image, and ranked among the top ones of the
state of the art on the [NUYv2](https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html) dataset while being simpler to train in a single phase than most competitors.

\[ Related: [ICIP 2018 paper](http://mcarvalho.ml/material/docs/2018/regression_losses_icip_2018.pdf) / [ECCV/W 2018 paper](http://www.sys.info.hiroshima-cu.ac.jp/3drw2018/procs/W17-01.pdf) / [video](https://www.youtube.com/watch?v=Zx7k5-xc-BE) \]


## SnapNet: Multi-view conv net for 3D semantic labeling 	 

![image-left]({{ site.url }}{{ site.baseurl }}/images/snapnet_semantic3d-icon.png){: .align-left}

[code](https://github.com/aboulch/snapnet)

With [Alexandre Boulch](), we conceived SnapNet, a multi-view conv net for semantic labeling of unstructured 3D point clouds. During more than one year, it led the [semantic3D leaderboard](http://semantic3d.net/view_results.php?chl=1) for 3D urban mapping, and still is among the top ones. In particular, it is computationally efficient and allows to deal with large datasets in tractable times. With Joris Guerry, we developped a variant which was aplied on robotics datasets such as NYUv2 or SunRGBD with excellent classification results.

\[ Related: [CaG 2017 paper](https://blesaux.github.io/files/2017-11-10-aboulch-snapnet-CAG17.pdf) /  [ICCV/W 2017 paper](http://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w13/Guerry_SnapNet-R_Consistent_3D_ICCV_2017_paper.pdf) \]



