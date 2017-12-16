---
layout: post
title: "Seeing into Darkness: Scotopic Visual Recognition"
date: 2016-10-03 05:03:45
categories: arXiv_CV
tags: arXiv_CV CNN Classification Recognition
author: Bo Chen, Pietro Perona
mathjax: true
---

* content
{:toc}

##### Abstract
Images are formed by counting how many photons traveling from a given set of directions hit an image sensor during a given time interval. When photons are few and far in between, the concept of `image' breaks down and it is best to consider directly the flow of photons. Computer vision in this regime, which we call `scotopic', is radically different from the classical image-based paradigm in that visual computations (classification, control, search) have to take place while the stream of photons is captured and decisions may be taken as soon as enough information is available. The scotopic regime is important for biomedical imaging, security, astronomy and many other fields. Here we develop a framework that allows a machine to classify objects with as few photons as possible, while maintaining the error rate below an acceptable threshold. A dynamic and asymptotically optimal speed-accuracy tradeoff is a key feature of this framework. We propose and study an algorithm to optimize the tradeoff of a convolutional network directly from lowlight images and evaluate on simulated images from standard datasets. Surprisingly, scotopic systems can achieve comparable classification performance as traditional vision systems while using less than 0.1% of the photons in a conventional image. In addition, we demonstrate that our algorithms work even when the illuminance of the environment is unknown and varying. Last, we outline a spiking neural network coupled with photon-counting sensors as a power-efficient hardware realization of scotopic algorithms.

##### Abstract (translated by Google)
通过计算在给定时间间隔内从给定方向行进的多少光子撞击图像传感器来形成图像。当光子很少时，“图像”的概念被打破，最好直接考虑光子的流动。计算机视觉在这个我们称之为“暗视”的体系中，与经典的基于图像的范式截然不同，因为视觉计算（分类，控制，搜索）必须发生，而光子流被捕获并且可能会做出决定只要有足够的信息可用。暗视法对于生物医学成像，安全，天文学和许多其他领域是重要的。在这里，我们开发了一个框架，允许一台机器用尽可能少的光子分类对象，同时保持错误率低于可接受的阈值。动态和渐近最佳的速度精度折衷是这个框架的一个关键特征。我们提出并研究一种算法来优化卷积网络直接从低光图像折衷和评估标准数据集的模拟图像。令人惊讶的是，暗视觉系统可以实现与传统视觉系统相当的分类性能，而在传统图像中使用的光子量小于0.1％。另外，我们证明我们的算法即使在环境照度未知且变化的情况下也能工作。最后，我们概述了一个带有光子计数传感器的尖峰神经网络，作为暗物质算法的高效率硬件实现。

##### URL
[https://arxiv.org/abs/1610.00405](https://arxiv.org/abs/1610.00405)

##### PDF
[https://arxiv.org/pdf/1610.00405](https://arxiv.org/pdf/1610.00405)

