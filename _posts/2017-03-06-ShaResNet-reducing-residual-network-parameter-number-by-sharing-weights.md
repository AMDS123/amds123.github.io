---
layout: post
title: "ShaResNet: reducing residual network parameter number by sharing weights"
date: 2017-03-06 13:49:15
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Alexandre Boulch
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Residual Networks have reached the state of the art in many image processing tasks such image classification. However, the cost for a gain in accuracy in terms of depth and memory is prohibitive as it requires a higher number of residual blocks, up to double the initial value. To tackle this problem, we propose in this paper a way to reduce the redundant information of the networks. We share the weights of convolutional layers between residual blocks operating at the same spatial scale. The signal flows multiple times in the same convolutional layer. The resulting architecture, called ShaResNet, contains block specific layers and shared layers. These ShaResNet are trained exactly in the same fashion as the commonly used residual networks. We show, on the one hand, that they are almost as efficient as their sequential counterparts while involving less parameters, and on the other hand that they are more efficient than a residual network with the same number of parameters. For example, a 152-layer-deep residual network can be reduced to 106 convolutional layers, i.e. a parameter gain of 39\%, while loosing less than 0.2\% accuracy on ImageNet.

##### Abstract (translated by Google)
深度残留网络在诸如图像分类等许多图像处理任务中已经达到了最新水平。但是，深度和内存方面的准确度提高的成本是高得惊人的，因为它需要更多数量的残留块，高达初始值的两倍。针对这个问题，本文提出了一种减少网络冗余信息的方法。我们共享在相同空间尺度下运行的残差块之间卷积层的权重。信号在相同的卷积层中多次流动。由此产生的架构，称为ShaResNet，包含块特定的图层和共享层。这些ShaResNet的训练方式与常用的残余网络完全相同。我们一方面表明，它们几乎和它们的顺序相同，但涉及的参数较少，另一方面，它们比具有相同参数数量的剩余网络更有效率。例如，152层深度的残留网络可以减少到106个卷积层，即参数增益为39％，同时在ImageNet上丢失小于0.2％的精度。

##### URL
[https://arxiv.org/abs/1702.08782](https://arxiv.org/abs/1702.08782)

##### PDF
[https://arxiv.org/pdf/1702.08782](https://arxiv.org/pdf/1702.08782)

