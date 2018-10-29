---
layout: post
title: "DifNet: Semantic Segmentation by Diffusion Networks"
date: 2018-10-26 16:41:39
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Prediction Detection
author: Peng Jiang, Fanglin Gu, Yunhai Wang, Changhe Tu, Baoquan Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Neural Networks (DNNs) have recently shown state of the art performance on semantic segmentation tasks, however, they still suffer from problems of poor boundary localization and spatial fragmented predictions. The difficulties lie in the requirement of making dense predictions from a long path model all at once since details are hard to keep when data goes through deeper layers. Instead, in this work, we decompose this difficult task into two relative simple sub-tasks: seed detection which is required to predict initial predictions without the need of wholeness and preciseness, and similarity estimation which measures the possibility of any two nodes belong to the same class without the need of knowing which class they are. We use one branch network for one sub-task each, and apply a cascade of random walks base on hierarchical semantics to approximate a complex diffusion process which propagates seed information to the whole image according to the estimated similarities. The proposed DifNet consistently produces improvements over the baseline models with the same depth and with the equivalent number of parameters, and also achieves promising performance on Pascal VOC and Pascal Context dataset. OurDifNet is trained end-to-end without complex loss functions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.08015](http://arxiv.org/abs/1805.08015)

##### PDF
[http://arxiv.org/pdf/1805.08015](http://arxiv.org/pdf/1805.08015)

