---
layout: post
title: "An Image Clustering Auto-Encoder Based on Predefined Evenly-Distributed Class Centroids and MMD Distance"
date: 2019-06-10 11:28:15
categories: arXiv_CV
tags: arXiv_CV
author: Qiuyu Zhu, Zhengyong Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose an end-to-end image clustering auto-encoder algorithm: ICAE. The algorithm uses PEDCC (Predefined Evenly-Distributed Class Centroids) as the clustering centers of the images, which ensures the inter-class distance of latent features is maximal, and adds data distribution constraint, data augmentation constraint, auto-encoder reconstruction loss constraint and latent features plus noise constraint to improve clustering performance. Specifically, we perform one-to-one data augmentation such as rotation, shear, and shift before data is input to the encoder to learn the more effective features. The data and the enhanced data are simultaneously input into the auto-encoder to obtain latent features and augmented latent features whose similarity are constrained by an augmentation loss. Then, making use of the MMD distance, we combine the latent features and augmented latent features to make their distribution close to the PEDCC distribution (uniform distribution between classes, Dirac distribution within the class) to further learn the features used for clustering. At the same time, the MSE of the original input image and reconstructed image is used as reconstruction constraint, and the noise is added to the latent features to build generalization constraint to improve the generalization ability. Finally, extensive experiments on three common datasets MNIST, Fashion-MNIST, COIL20 are conducted. The experimental results show that the algorithm has achieved the best clustering results so far, and also has good generalization ability. In addition, we can use the pre-defined PEDCC class centers, and the decoding module of the auto-encoder to clearly generate the samples of each class. The code can be downloaded at xxx!

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.03905](http://arxiv.org/abs/1906.03905)

##### PDF
[http://arxiv.org/pdf/1906.03905](http://arxiv.org/pdf/1906.03905)

