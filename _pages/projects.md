---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

My current projects include:

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}




# Scene Understanding

Scene understanding is a fundamental task in computer vision which requires understanding the scene's geometry and semantic structure.
Initially, I worked on a semantic segmentation algorithm called [SegNet](http://mi.eng.cam.ac.uk/projects/segnet/).
More recently, I have been interested in learning depth, instance and semantic segmentation from a [unified deep learning architecture](https://arxiv.org/pdf/1705.07115.pdf).

![image-center]({{ site.url }}{{ site.baseurl }}/assets/images/multitask.jpg){: .align-center}

---

# Bayesian Deep Learning

Deep learning is great for achieving state-of-the-art results, however these models cannot understand what they don't know.
Bayesian deep learning (BDL) is a very exciting framework for understanding our model's uncertainty.
[This paper](https://arxiv.org/pdf/1703.04977.pdf) is an introduction to Bayesian deep learning for computer vision. 
I have also found BDL useful for [localisation](http://arxiv.org/abs/1509.05909) and [scene understanding](http://arxiv.org/abs/1511.02680).

{% include gallery id="gallery_uncertainty" caption="Bayesian deep learning for semantic segmentation. From left to right: input image, semantic segmentation and model uncertainty." %}
