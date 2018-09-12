---
layout: post
title: "Efficient Fusion of Sparse and Complementary Convolutions"
date: 2018-09-11 03:18:39
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse CNN Classification Detection
author: Chun-Fu Chen, Quanfu Fan, Marco Pistoia, Gwo Giun Lee
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new method to create compact convolutional neural networks (CNNs) by exploiting sparse convolutions. Different from previous works that learn sparsity in models, we directly employ hand-crafted kernels with regular sparse patterns, which result in the computational gain in practice without sophisticated and dedicated software or hardware. The core of our approach is an efficient network module that linearly combines sparse kernels to yield feature representations as strong as those from regular kernels. We integrate this module into various network architectures and demonstrate its effectiveness on three vision tasks, object classification, localization and detection. For object classification and localization, our approach achieves comparable or better performance than several baselines and related works while providing lower computational costs with fewer parameters (on average, a $2-4\times$ reduction of convolutional parameters and computation). For object detection, our approach leads to a VGG-16-based Faster RCNN detector that is 12.4$\times$ smaller and about 3$\times$ faster than the baseline.

##### Abstract (translated by Google)
我们提出了一种通过利用稀疏卷积来创建紧凑卷积神经网络（CNN）的新方法。与以前学习模型中的稀疏性的工作不同，我们直接使用具有规则稀疏模式的手工制作的内核，这导致实践中的计算增益，而无需复杂的专用软件或硬件。我们的方法的核心是一个高效的网络模块，它线性地组合稀疏内核，以产生与常规内核一样强大的特征表示。我们将该模块集成到各种网络架构中，并展示其在三个视觉任务，对象分类，定位和检测方面的有效性。对于对象分类和定位，我们的方法实现了与几个基线和相关工作相当或更好的性能，同时以更少的参数提供更低的计算成本（平均而言，卷积参数和计算的减少$ 2-4倍）。对于物体检测，我们的方法导致基于VGG-16的Faster RCNN检测器比基线小12.4 $ \倍，比基线快3美元/倍。

##### URL
[https://arxiv.org/abs/1808.02167](https://arxiv.org/abs/1808.02167)

##### PDF
[https://arxiv.org/pdf/1808.02167](https://arxiv.org/pdf/1808.02167)

