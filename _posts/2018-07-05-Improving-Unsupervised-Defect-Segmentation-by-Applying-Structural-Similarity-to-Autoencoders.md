---
layout: post
title: "Improving Unsupervised Defect Segmentation by Applying Structural Similarity to Autoencoders"
date: 2018-07-05 14:07:23
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Paul Bergmann, Sindy L&#xf6;we, Michael Fauser, David Sattlegger, Carsten Steger
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional autoencoders have emerged as popular models for unsupervised defect segmentation on image data. Most commonly, this task is performed by thresholding a pixel-wise reconstruction error based on an $\ell^p$ distance. However, this procedure generally leads to high novelty scores whenever the reconstruction encompasses slight localization inaccuracies around edges. We show that this problem prevents these approaches from being applied to complex real-world scenarios and that it cannot be easily avoided by employing more elaborate architectures. Instead, we propose to use a perceptual loss function based on structural similarity. Our approach achieves state-of-the-art performance on a real-world dataset of nanofibrous materials, while being trained end-to-end without requiring additional priors such as pretrained networks or handcrafted features.

##### Abstract (translated by Google)
卷积自动编码器已经成为用于图像数据的无监督缺陷分割的流行模型。最常见的是，此任务是通过基于$ \ ell ^ p $距离对像素方式重建错误进行阈值处理来执行的。然而，每当重建包含边缘周围的轻微定位不准确时，该过程通常导致高新颖性分数。我们表明，这个问题阻止了这些方法应用于复杂的现实场景，并且通过采用更复杂的架构无法轻易避免。相反，我们建议使用基于结构相似性的感知损失函数。我们的方法在真实世界的纳米纤维材料数据集上实现了最先进的性能，同时进行端到端的培训，无需额外的先验，如预训练网络或手工制作的功能。

##### URL
[http://arxiv.org/abs/1807.02011](http://arxiv.org/abs/1807.02011)

##### PDF
[http://arxiv.org/pdf/1807.02011](http://arxiv.org/pdf/1807.02011)

