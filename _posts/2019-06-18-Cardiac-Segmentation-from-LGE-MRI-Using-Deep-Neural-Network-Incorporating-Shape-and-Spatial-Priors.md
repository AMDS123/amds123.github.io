---
layout: post
title: "Cardiac Segmentation from LGE MRI Using Deep Neural Network Incorporating Shape and Spatial Priors"
date: 2019-06-18 02:36:34
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial Segmentation RNN
author: Qian Yue, Xinzhe Luo, Qing Ye, Lingchao Xu, Xiahai Zhuang
mathjax: true
---

* content
{:toc}

##### Abstract
Cardiac segmentation from late gadolinium enhancement MRI is an important task in clinics to identify and evaluate the infarction of myocardium. The automatic segmentation is however still challenging, due to the heterogeneous intensity distributions and indistinct boundaries in the images. In this paper, we propose a new method, based on deep neural networks (DNN), for fully automatic segmentation. The proposed network, referred to as SRSCN, comprises a shape reconstruction neural network (SRNN) and a spatial constraint network (SCN). SRNN aims to maintain a realistic shape of the resulting segmentation. It can be pre-trained by a set of label images, and then be embedded into a unified loss function as a regularization term. Hence, no manually designed feature is needed. Furthermore, SCN incorporates the spatial information of the 2D slices. It is formulated and trained with the segmentation network via the multi-task learning strategy. We evaluated the proposed method using 45 patients and compared with two state-of-the-art regularization schemes, i.e., the anatomically constraint neural network and the adversarial neural network. The results show that the proposed SRSCN outperformed the conventional schemes, and obtained a Dice score of 0.758(std=0.227) for myocardial segmentation, which compares with 0.757(std=0.083) from the inter-observer variations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07347](http://arxiv.org/abs/1906.07347)

##### PDF
[http://arxiv.org/pdf/1906.07347](http://arxiv.org/pdf/1906.07347)

