---
layout: post
title: "Data Augmentation using Random Image Cropping and Patching for Deep CNNs"
date: 2018-11-22 06:07:40
categories: arXiv_CV
tags: arXiv_CV Image_Caption Regularization Caption CNN Classification
author: Ryo Takahashi, Takashi Matsubara, Kuniaki Uehara
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks (CNNs) have achieved remarkable results in image processing tasks. However, their high expression ability risks overfitting. Consequently, data augmentation techniques have been proposed to prevent overfitting while enriching datasets. Recent CNN architectures with more parameters are rendering traditional data augmentation techniques insufficient. In this study, we propose a new data augmentation technique called random image cropping and patching (RICAP) which randomly crops four images and patches them to create a new training image. Moreover, RICAP mixes the class labels of the four images, resulting in an advantage similar to label smoothing. We evaluated RICAP with current state-of-the-art CNNs (e.g., the shake-shake regularization model) by comparison with competitive data augmentation techniques such as cutout and mixup. RICAP achieves a new state-of-the-art test error of $2.19\%$ on CIFAR-10. We also confirmed that deep CNNs with RICAP achieve better results on classification tasks using CIFAR-100 and ImageNet and an image-caption retrieval task using Microsoft COCO.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.09030](http://arxiv.org/abs/1811.09030)

##### PDF
[http://arxiv.org/pdf/1811.09030](http://arxiv.org/pdf/1811.09030)

