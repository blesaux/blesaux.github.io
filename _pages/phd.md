---
layout: single
permalink: /publications/phd
title: "Doctorate (PhD)"
author_profile: true
---

## Doctorate (_PhD_)

[INRIA Imedia](https://www-rocq.inria.fr/imedia/) and [University Versailles-Saint-Quentin](https://www.uvsq.fr/uvsq)

July 2003

[ [pdf](http://blesaux.free.fr/papers/lesaux-these.pdf) / [theses.fr notice](https://theses.fr/2003VERS0013) / [summary]({{ site.url }}/publications/phd#summary) / [résumé]({{ site.url }}/publications/phd#resume) ]

---

## Summary
<a name="summary"></a>

**Title**: Unsupervised classification and learning-based personalization : application to image database browsing

**Keywords**: Machine learning; Support Vector Machines; Clustering; Image Analysis; Multimedia Databases

**Abstract**:

Due to the dramatic increase of the number of multimedia documents, content-based image retrieval has became an active research field, and applications such as digital libraries and video-on-demand emerged as real-life facts. If the feasibility of image retrieval using visual similarity has been proven, there are few attempts so far to give the user a way to deal globally with a large image collection.

We developed a clustering method able to find image categories in an image database. Such an automatic categorization requires to determine automatically the number of categories and to deal with challenging conditions since clusters are noisy, with various shapes and densities. Clustering is performed by minimizing a new Competitive Agglomeration objective function, in which competition is adaptive to the category densities. Beside, a noise cluster collects outliers, i.e. images which does not belong to a category, to prevent them to degrade clustering. By picking a prototype in each category, we are able to build a summary which could be used as a page zero for a CBIR system.

In a second step, we let the user organize the image collection. SVM learning is used to process feedback of category relevance. Only a few examples are required to filter and re-classify images to the user's personally-defined categories. Training with such a small set is made possible by using the SVM kernel as a metric in the feature space and defining a distribution model for the data. This leads to the precise selection of relevant images.

Our method has been applied with success in an industrial context to macro-segmentation of video. Our system could generate a summary of broadcast news for fast Internet viewing. Another application is the clustering of similar image regions to allow image retrieval using query composition with multiple region prototypes.
---

## Résumé
<a name="resume"></a>

**Titre** : Classification non exclusive et personnalisation par apprentissage : application à la navigation dans les bases d'images

**Mots clés** : Apprentissage machine; Machines à Vecteurs de Support; Classification non-supervisée; Analyse d'images; Base d'images multimédia

**Résumé** :

Dans le cadre de la recherche d'images par le contenu, nous nous sommes intéressés aux méthodes de résumé et d'aide à la navigation pour les bases d'images. 

Nous avons développé une méthode de classification non-exclusive capable de catégoriser l'espace de description des images pour regrouper les images d'apparences visuelles similaires. En définissant une nouvelle fonction de Compétition Agglomérative où la compétition s'adapte à la densité des atégories, l'algorithme ARC (Adaptive Robust Competition) permet de résoudre les difficultés suivantes : 
* déterminer automatiquement le nombre de classes,
* gérer les données bruitées diffuses,
* prendre en compte les densités et les formes variables des classes.

Dans un deuxième temps, nous permettons à l'utilisateur de contrôler la pertinence des classes obtenues. Un apprentissage basé sur une machine à vecteurs de support permet de personnaliser les classes d'images.
