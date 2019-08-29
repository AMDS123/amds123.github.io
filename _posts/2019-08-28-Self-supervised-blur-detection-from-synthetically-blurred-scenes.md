---
layout: post
title: "Self-supervised blur detection from synthetically blurred scenes"
date: 2019-08-28 10:58:55
categories: arXiv_CV
tags: arXiv_CV Segmentation Weakly_Supervised Deep_Learning Detection
author: Aitor Alvarez-Gila, Adrian Galdran, Estibaliz Garrote, Joost van de Weijer
mathjax: true
---

* content
{:toc}

##### Abstract
Blur detection aims at segmenting the blurred areas of a given image. Recent deep learning-based methods approach this problem by learning an end-to-end mapping between the blurred input and a binary mask representing the localization of its blurred areas. Nevertheless, the effectiveness of such deep models is limited due to the scarcity of datasets annotated in terms of blur segmentation, as blur annotation is labour intensive. In this work, we bypass the need for such annotated datasets for end-to-end learning, and instead rely on object proposals and a model for blur generation in order to produce a dataset of synthetically blurred images. This allows us to perform self-supervised learning over the generated image and ground truth blur mask pairs using CNNs, defining a framework that can be employed in purely self-supervised, weakly supervised or semi-supervised configurations. Interestingly, experimental results of such setups over the largest blur segmentation datasets available show that this approach achieves state of the art results in blur segmentation, even without ever observing any real blurred image.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.10638](http://arxiv.org/abs/1908.10638)

##### PDF
[http://arxiv.org/pdf/1908.10638](http://arxiv.org/pdf/1908.10638)

