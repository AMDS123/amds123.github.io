---
layout: post
title: "Efficient Hand Articulations Tracking using Adaptive Hand Model and Depth map"
date: 2015-10-18 03:21:48
categories: arXiv_CV
tags: arXiv_CV Knowledge Tracking Classification Detection
author: Byeongkeun Kang, Yeejin Lee, Truong Q. Nguyen
mathjax: true
---

* content
{:toc}

##### Abstract
Real-time hand articulations tracking is important for many applications such as interacting with virtual / augmented reality devices or tablets. However, most of existing algorithms highly rely on expensive and high power-consuming GPUs to achieve real-time processing. Consequently, these systems are inappropriate for mobile and wearable devices. In this paper, we propose an efficient hand tracking system which does not require high performance GPUs. In our system, we track hand articulations by minimizing discrepancy between depth map from sensor and computer-generated hand model. We also initialize hand pose at each frame using finger detection and classification. Our contributions are: (a) propose adaptive hand model to consider different hand shapes of users without generating personalized hand model; (b) improve the highly efficient frame initialization for robust tracking and automatic initialization; (c) propose hierarchical random sampling of pixels from each depth map to improve tracking accuracy while limiting required computations. To the best of our knowledge, it is the first system that achieves both automatic hand model adjustment and real-time tracking without using GPUs.

##### Abstract (translated by Google)
实时的手部关节跟踪对于许多应用程序很重要，例如与虚拟/增强现实设备或平板电脑进行交互。然而，现有的大多数算法高度依赖于昂贵和高功耗的GPU来实现实时处理。因此，这些系统不适用于移动和可穿戴设备。在本文中，我们提出了一个高效的手动跟踪系统，不需要高性能的GPU。在我们的系统中，我们通过最小化传感器的深度图和计算机生成的手模型之间的差异来跟踪手关节。我们还使用手指检测和分类来初始化每一帧的手姿势。我们的贡献是：（a）提出自适应手模型来考虑用户的不同手形而不产生个性化的手模型; （b）改进高效的帧初始化以实现稳健的跟踪和自动初始化; （c）提出来自每个深度图的像素的分级随机采样，以提高跟踪精度，同时限制所需的计算。据我们所知，这是第一个在不使用GPU的情况下实现自动手动模型调整和实时跟踪的系统。

##### URL
[https://arxiv.org/abs/1510.00981](https://arxiv.org/abs/1510.00981)

##### PDF
[https://arxiv.org/pdf/1510.00981](https://arxiv.org/pdf/1510.00981)

