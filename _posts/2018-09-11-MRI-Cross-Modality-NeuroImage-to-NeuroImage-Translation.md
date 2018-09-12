---
layout: post
title: "MRI Cross-Modality NeuroImage-to-NeuroImage Translation"
date: 2018-09-11 07:17:13
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN CNN Deep_Learning
author: Qianye Yang, Nannan Li, Zixu Zhao, Xingyu Fan, Eric I-Chao Chang, Yan Xu
mathjax: true
---

* content
{:toc}

##### Abstract
We present a cross-modality generation framework that learns to generate translated modalities from given modalities in MR images without real acquisition. Our proposed method performs NeuroImage-to-NeuroImage translation (abbreviated as N2N) by means of a deep learning model that leverages conditional generative adversarial networks (cGANs). Our framework jointly exploits the low-level features (pixel-wise information) and high-level representations (e.g. brain tumors, brain structure like gray matter, etc.) between cross modalities which are important for resolving the challenging complexity in brain structures. Our framework can serve as an auxiliary method in clinical diagnosis and has great application potential. Based on our proposed framework, we first propose a method for cross-modality registration by fusing the deformation fields to adopt the cross-modality information from translated modalities. Second, we propose an approach for MRI segmentation, translated multichannel segmentation (TMS), where given modalities, along with translated modalities, are segmented by fully convolutional networks (FCN) in a multichannel manner. Both of these two methods successfully adopt the cross-modality information to improve the performance without adding any extra data. Experiments demonstrate that our proposed framework advances the state-of-the-art on five brain MRI datasets. We also observe encouraging results in cross-modality registration and segmentation on some widely adopted brain datasets. Overall, our work can serve as an auxiliary method in clinical diagnosis and be applied to various tasks in medical fields. 
 Keywords: image-to-image, cross-modality, registration, segmentation, brain MRI

##### Abstract (translated by Google)
我们提出了一种跨模态生成框架，该框架学习如何在没有实际采集的情况下从MR图像中的给定模态生成翻译模态。我们提出的方法通过利用条件生成对抗网络（cGAN）的深度学习模型执行NeuroImage-to-NeuroImage翻译（缩写为N2N）。我们的框架联合利用交叉模式之间的低级特征（像素信息）和高级表示（例如脑肿瘤，像灰质等脑结构），这对于解决大脑结构中具有挑战性的复杂性是重要的。我们的框架可以作为临床诊断的辅助方法，具有很大的应用潜力。基于我们提出的框架，我们首先提出了一种通过融合变形场来采用来自翻译模态的跨模态信息来进行跨模态登记的方法。其次，我们提出了一种用于MRI分割，翻译多通道分割（TMS）的方法，其中给定的模态以及翻译的模态通过完全卷积网络（FCN）以多通道方式分段。这两种方法都成功地采用了跨模态信息来提高性能，而无需添加任何额外数据。实验表明，我们提出的框架推进了五个脑MRI数据集的最新技术。我们还观察到在一些广泛采用的大脑数据集上进行跨模态配准和分割的令人鼓舞的结果。总的来说，我们的工作可以作为临床诊断的辅助方法，并应用于医学领域的各种任务。
 关键词：图像到图像，交叉模态，配准，分割，脑MRI

##### URL
[http://arxiv.org/abs/1801.06940](http://arxiv.org/abs/1801.06940)

##### PDF
[http://arxiv.org/pdf/1801.06940](http://arxiv.org/pdf/1801.06940)

