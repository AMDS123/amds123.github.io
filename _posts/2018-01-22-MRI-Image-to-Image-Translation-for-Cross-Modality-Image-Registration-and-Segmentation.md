---
layout: post
title: "MRI Image-to-Image Translation for Cross-Modality Image Registration and Segmentation"
date: 2018-01-22 02:53:28
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN CNN Deep_Learning
author: Qianye Yang, Nannan Li, Zixu Zhao, Xingyu Fan, Eric I-Chao Chang, Yan Xu
mathjax: true
---

* content
{:toc}

##### Abstract
We develop a novel cross-modality generation framework that learns to generate predicted modalities from given modalities in MR images without real acquisition. Our proposed method performs image-to-image translation by means of a deep learning model that leverages conditional generative adversarial networks (cGANs). Our framework jointly exploits the low-level features (pixel-wise information) and high-level representations (e.g. brain tumors, brain structure like gray matter, etc.) between cross modalities which are important for resolving the challenging complexity in brain structures. Based on our proposed framework, we first propose a method for cross-modality registration by fusing the deformation fields to adopt the cross-modality information from predicted modalities. Second, we propose an approach for MRI segmentation, translated multichannel segmentation (TMS), where given modalities, along with predicted modalities, are segmented by fully convolutional networks (FCN) in a multi-channel manner. Both these two methods successfully adopt the cross-modality information to improve the performance without adding any extra data. Experiments demonstrate that our proposed framework advances the state-of-the-art on five MRI datasets. We also observe encouraging results in cross-modality registration and segmentation on some widely adopted datasets. Overall, our work can serve as an auxiliary method in clinical diagnosis and be applied to various tasks in medical fields. Keywords: Image-to-image, cross-modality, registration, segmentation, MRI

##### Abstract (translated by Google)
我们开发了一种新的跨模态生成框架，学习如何从MR图像中的给定模态生成预测模式，而不需要真正的采集。我们提出的方法通过利用条件生成对抗网络（cGAN）的深度学习模型执行图像到图像的转换。我们的框架共同利用交叉形式之间的低级特征（逐像素信息）和高级表示（例如脑肿瘤，脑结构像灰质等），这对于解决大脑结构中具有挑战性的复杂性是重要的。基于我们提出的框架，我们首先提出一种交叉模态配准的方法，通过融合变形场来采用预测模态的交叉模态信息。其次，我们提出了一种用于MRI分割的方法，翻译多通道分割（TMS），其中给定的模式以及预测的模态通过完全卷积网络（FCN）以多通道方式分割。这两种方法都成功地采用了跨模态信息来提高性能，而不增加额外的数据。实验表明，我们提出的框架提高了五个MRI数据集的最新水平。我们也观察到一些广泛采用的数据集在跨模态注册和分割方面令人鼓舞的结果。总之，我们的工作可以作为临床诊断的辅助手段，应用于医学领域的各种任务。关键词：图像到图像，交叉模态，配准，分割，MRI

##### URL
[https://arxiv.org/abs/1801.06940](https://arxiv.org/abs/1801.06940)

##### PDF
[https://arxiv.org/pdf/1801.06940](https://arxiv.org/pdf/1801.06940)

