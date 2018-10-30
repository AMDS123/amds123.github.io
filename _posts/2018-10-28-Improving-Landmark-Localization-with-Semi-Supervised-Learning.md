---
layout: post
title: "Improving Landmark Localization with Semi-Supervised Learning"
date: 2018-10-28 15:05:52
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Classification Prediction Detection
author: Sina Honari, Pavlo Molchanov, Stephen Tyree, Pascal Vincent, Christopher Pal, Jan Kautz
mathjax: true
---

* content
{:toc}

##### Abstract
We present two techniques to improve landmark localization in images from partially annotated datasets. Our primary goal is to leverage the common situation where precise landmark locations are only provided for a small data subset, but where class labels for classification or regression tasks related to the landmarks are more abundantly available. First, we propose the framework of sequential multitasking and explore it here through an architecture for landmark localization where training with class labels acts as an auxiliary signal to guide the landmark localization on unlabeled data. A key aspect of our approach is that errors can be backpropagated through a complete landmark localization model. Second, we propose and explore an unsupervised learning technique for landmark localization based on having a model predict equivariant landmarks with respect to transformations applied to the image. We show that these techniques, improve landmark prediction considerably and can learn effective detectors even when only a small fraction of the dataset has landmark labels. We present results on two toy datasets and four real datasets, with hands and faces, and report new state-of-the-art on two datasets in the wild, e.g. with only 5\% of labeled images we outperform previous state-of-the-art trained on the AFLW dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1709.01591](http://arxiv.org/abs/1709.01591)

##### PDF
[http://arxiv.org/pdf/1709.01591](http://arxiv.org/pdf/1709.01591)

