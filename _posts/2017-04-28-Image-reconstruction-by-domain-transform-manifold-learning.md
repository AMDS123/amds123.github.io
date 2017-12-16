---
layout: post
title: "Image reconstruction by domain transform manifold learning"
date: 2017-04-28 08:24:03
categories: arXiv_CV
tags: arXiv_CV Sparse Knowledge
author: Bo Zhu, Jeremiah Z. Liu, Bruce R. Rosen, Matthew S. Rosen
mathjax: true
---

* content
{:toc}

##### Abstract
Image reconstruction plays a critical role in the implementation of all contemporary imaging modalities across the physical and life sciences including optical, MRI, CT, PET, and radio astronomy. During an image acquisition, the sensor encodes an intermediate representation of an object in the sensor domain, which is subsequently reconstructed into an image by an inversion of the encoding function. Image reconstruction is challenging because analytic knowledge of the inverse transform may not exist a priori, especially in the presence of sensor non-idealities and noise. Thus, the standard reconstruction approach involves approximating the inverse function with multiple ad hoc stages in a signal processing chain whose composition depends on the details of each acquisition strategy, and often requires expert parameter tuning to optimize reconstruction performance. We present here a unified framework for image reconstruction, AUtomated TransfOrm by Manifold APproximation (AUTOMAP), which recasts image reconstruction as a data-driven, supervised learning task that allows a mapping between sensor and image domain to emerge from an appropriate corpus of training data. We implement AUTOMAP with a deep neural network and exhibit its flexibility in learning reconstruction transforms for a variety of MRI acquisition strategies, using the same network architecture and hyperparameters. We further demonstrate its efficiency in sparsely representing transforms along low-dimensional manifolds, resulting in superior immunity to noise and reconstruction artifacts compared with conventional handcrafted reconstruction methods. In addition to improving the reconstruction performance of existing acquisition methodologies, we anticipate accelerating the discovery of new acquisition strategies across modalities as the burden of reconstruction becomes lifted by AUTOMAP and learned-reconstruction approaches.

##### Abstract (translated by Google)
图像重建在整个物理和生命科学（包括光学，MRI，CT，PET和射电天文学）的所有当代成像模式的实施中发挥着至关重要的作用。在图像采集期间，传感器对传感器域中的对象的中间表示进行编码，随后通过编码函数的反转将其重构为图像。图像重构是具有挑战性的，因为逆变换的分析知识可能不是先验的，特别是在传感器非理想和噪声的情况下。因此，标准重构方法包括在信号处理链中利用多个特定阶段近似反函数，其组成依赖于每个采集策略的细节，并且通常需要专家参数调整来优化重建性能。我们在这里提出一个统一的图像重建框架，通过流形APproximation（AUTOMAP）进行AUtomated TransfOrm，将图像重建改造为数据驱动的监督学习任务，允许传感器和图像域之间的映射从适当的训练数据语料库。我们使用深度神经网络来实现AUTOMAP，并且使用相同的网络架构和超参数在各种MRI采集策略中表现出其学习重建转换的灵活性。我们进一步证明了它在低维流形中稀疏表示变换的效率，与传统的手工重建方法相比，对噪声和重建伪影具有更好的免疫性。除了提高现有采购方法的重建绩效之外，我们预计随着AUTOMAP和学习重建方法提升重建负担，我们将加快在各种模式下发现新的采购策略。

##### URL
[https://arxiv.org/abs/1704.08841](https://arxiv.org/abs/1704.08841)

##### PDF
[https://arxiv.org/pdf/1704.08841](https://arxiv.org/pdf/1704.08841)

