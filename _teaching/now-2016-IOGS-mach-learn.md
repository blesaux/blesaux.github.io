---
title: "Pattern recognition and Machine Learning"
collection: teaching
level: "Graduate course"
type: "Uni"
permalink: /teaching/IOGS-machine-learning
venue: "Institut d'Optique Graduate School"
date: 2020-02-18
period: 2016 - now
location: "Palaiseau, France"
---

(with [François Goudail](https://www.lcf.institutoptique.fr/lcf-en/Groupes-de-recherche/SPIM/Membres/Permanents/Francois-Goudail), [Stéphane Herbin](http://www.onera.fr/fr/staff/stephane-herbin), Adrien Chan Hon Tong, [Alexandre Boulch](https://aboulch.github.io).).

2020 Material:

[Description in the IOGS Course Panel - SynapseS](https://synapses.institutoptique.fr/catalogue/2018-2019/ue/832/9P441SCI-apprentissage-et-reconnaissance-de-formes)

Colab notebook can be saved in you own environment using the "Copy to drive" item in the "File" menu.

| Date | Instructor | Topic | Course | Exercises |
| --- | --- | --- | --- | --- |
| 14/01 | SH | Introduction to Machine Learning | course #1 | --- |
| 20/01 | BLS | Decision trees, random forests and boosting | [Course #2](../courses/IOGS_ARDF_2020_02_arbres_et_ensembles.pdf) | [ipynb](../courses/IOGS_ARF_TP_tree_and_forest.ipynb) / [colab](https://colab.research.google.com/drive/1xWN7E10pUTg7bPYoz3q1xRda5JRpYamK) / [smile ref data for Olivetti faces](../courses/results-smile-GT-BLS.xml) / [ipynb results](../courses/IOGS_ARF_TP_RESULT_tree_and_forest.ipynb) / [colab results](https://colab.research.google.com/drive/16xuX62nuaSPsFcivHwdC3hk5y1sCTuXk) |
| 21/01 | ACHT | Neural Networks | course #3 | --- |
| 27/01 | SH | Support Vector Machines | course #4 | --- |
| 28/01 | BLS | Dimensionality reduction and clustering | [Course #5](../courses/IOGS_ARDF_2020_05_non_supervis.pdf) | [ipynb](../IOGS_ARF_TP_courses/pca_and_clustering.ipynb) / [colab](https://colab.research.google.com/drive/1HYnfKn4S-EMGbuaJviFMx9NQ4Q71ZhU6) / [colab results](https://colab.research.google.com/drive/14XYlnEyJw5z5aAVvHkPI8Mp1TXlM-DUv)  |
| 03/02 | ACHT | Deep Learning | Course #6 | --- |
| 10/02 | SH | --- | Exam | mini-project starts: cell segmentation / adversarial attacks / dehazing (see below) |
| 11/02 | SH | Regression | Course #8 | mini-project |
| 18/02 | BLS | Generative Networks and Auto-encoders | [Course #9](../courses/IOGS_ARDF_2020_09_AE_GANs.pdf) | mini-project: [data-loaders available](http://www.boulch.eu/teaching/iogs-rdf) |
| 25/02 | ACHT | Deep learning applications | Course #10 | mini-project ends |


## Dehazing mini project.

The Dehazing mini project span over 4 exercise sessions. It is based on the [NTIRE 2020](http://www.vision.ee.ethz.ch/ntire20/) challenge on [Non homogeneous dehazing](https://competitions.codalab.org/competitions/22236). The goal is to dehaze some images, i.e. removing haze, fog, mist and other smoke.

On the [codalab page](https://competitions.codalab.org/competitions/22236) of the challenge, one can register and get access to the data. Data consists of a training set of 45 pairs of hazy and clean images, and a validation set of 5 hazy images.

We provide jupyter notebooks:
* One to parse the images and save them in numpy arrays: [im2npy.ipynb](../courses/im2npy.ipynb)
* A DataLoader for subsequent machine learning processing in pytorch (credit: [A. Boulch[http://www.boulch.eu/teaching/iogs-rdf)): [dehazing.ipynb](../courses/dehazing.ipynb)

Prepared numpy arrays can be downloaded: [Train data](https://drive.google.com/file/d/1yHCCPyBXEHd0YUmnmF6AnLBb9qVp0yOr/view?usp=sharing) / [Train GT](https://drive.google.com/file/d/1Id6c3K8-O3GfSO0L60NrpGxKhejUIcJi/view?usp=sharing) / [Validation data](https://drive.google.com/file/d/172GD31CUwsBOpjZQFTbPqztxm9OFy22N/view?usp=sharing). Copy data locally, or put them in your own drive for use on colab.


 <!--  / [ipynb results](../courses/IOGS_ARF_TP_RESULT_tree_and_forest.ipynb) / [colab results](https://colab.research.google.com/drive/16xuX62nuaSPsFcivHwdC3hk5y1sCTuXk) -->

 <!-- / [colab results](https://colab.research.google.com/drive/14XYlnEyJw5z5aAVvHkPI8Mp1TXlM-DUv)  -->

<!-- 
2019 Material:

[Description in the IOGS Course Panel - SynapseS](https://synapses.institutoptique.fr/catalogue/2018-2019/ue/832/9P441SCI-apprentissage-et-reconnaissance-de-formes)

Colab notebook can be saved in you own environment using the "Copy to drive" item in the "File" menu.

| Instructor | Topic | Course | Exercises |
| --- | --- | --- | --- |
| SH | Introduction to Machine Learning | course #1 | --- |
| SH | Support Vector Machines | course #2 | --- |
| BLS | Decision trees, random forests and boosting | [Course #3](../courses/IOGS_ARF_2019_App_03_arbres_et_ensembles.pdf) | [ipynb](../courses/IOGS_ARF_TP_tree_and_forest.ipynb) / [colab](https://colab.research.google.com/drive/1xWN7E10pUTg7bPYoz3q1xRda5JRpYamK) / [smile ref data for Olivetti faces](../courses/results-smile-GT-BLS.xml) / [ipynb results](../courses/IOGS_ARF_TP_RESULT_tree_and_forest.ipynb) / [colab results](https://colab.research.google.com/drive/16xuX62nuaSPsFcivHwdC3hk5y1sCTuXk) |
| AB | Neural Networks | [course #4](http://www.boulch.eu/teaching/iogs-rdf) | --- |
| BLS | Dimensionality reduction and clustering | [Course #5](../courses/IOGS_ARF_2019_App_04_PCA_clustering.pdf) | [ipynb](../IOGS_ARF_TP_courses/pca_and_clustering.ipynb) / [colab](https://colab.research.google.com/drive/1HYnfKn4S-EMGbuaJviFMx9NQ4Q71ZhU6) / [colab results](https://colab.research.google.com/drive/14XYlnEyJw5z5aAVvHkPI8Mp1TXlM-DUv) |
| AB | Deep Learning | [Course #6](http://www.boulch.eu/teaching/iogs-rdf) | --- |
| SH | --- | Exam | mini-project starts |
| SH | Regression | Course #8 | mini-project |
| BLS | Generative Networks and Auto-encoders | [Course #9](../courses/IOGS_ARF_2019_App_09_AE_GANs.pdf) | mini-project: [data-loaders available](http://www.boulch.eu/teaching/iogs-rdf) |
| AB | Recurrent Neural Networks | Course #10 | mini-project ends |

-->

