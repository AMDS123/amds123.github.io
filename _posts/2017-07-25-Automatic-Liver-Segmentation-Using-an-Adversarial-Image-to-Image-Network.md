---
layout: post
title: "Automatic Liver Segmentation Using an Adversarial Image-to-Image Network"
date: 2017-07-25 15:16:07
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation CNN
author: Dong Yang, Daguang Xu, S. Kevin Zhou, Bogdan Georgescu, Mingqing Chen, Sasa Grbic, Dimitris Metaxas, Dorin Comaniciu
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic liver segmentation in 3D medical images is essential in many clinical applications, such as pathological diagnosis of hepatic diseases, surgical planning, and postoperative assessment. However, it is still a very challenging task due to the complex background, fuzzy boundary, and various appearance of liver. In this paper, we propose an automatic and efficient algorithm to segment liver from 3D CT volumes. A deep image-to-image network (DI2IN) is first deployed to generate the liver segmentation, employing a convolutional encoder-decoder architecture combined with multi-level feature concatenation and deep supervision. Then an adversarial network is utilized during training process to discriminate the output of DI2IN from ground truth, which further boosts the performance of DI2IN. The proposed method is trained on an annotated dataset of 1000 CT volumes with various different scanning protocols (e.g., contrast and non-contrast, various resolution and position) and large variations in populations (e.g., ages and pathology). Our approach outperforms the state-of-the-art solutions in terms of segmentation accuracy and computing efficiency.

##### Abstract (translated by Google)
三维医学图像中的自动肝脏分割在许多临床应用中是必不可少的，如肝病的病理诊断，手术计划和术后评估。但是，由于背景复杂，边界模糊，肝脏表现不同，仍然是一个非常具有挑战性的任务。在本文中，我们提出了一种自动和高效的算法来从三维CT体积中分割肝脏。首先部署一个深度图像到图像网络（DI2IN）来生成肝脏分割，采用卷积编码器 - 解码器架构，结合多级特征级联和深度监督。然后在训练过程中利用对抗网络将DI2IN的输出与地面事实进行区分，从而进一步提升DI2IN的性能。所提出的方法在具有各种不同扫描协议（例如，对比度和非对比度，各种分辨率和位置）以及群体（例如年龄和病理）的大的变化的1000个CT体积的注释数据集上被训练。我们的方法在分割准确性和计算效率方面胜过了最先进的解决方案。

##### URL
[https://arxiv.org/abs/1707.08037](https://arxiv.org/abs/1707.08037)

##### PDF
[https://arxiv.org/pdf/1707.08037](https://arxiv.org/pdf/1707.08037)

