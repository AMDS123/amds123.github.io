---
layout: post
title: "EraseReLU: A Simple Way to Ease the Training of Deep Convolution Neural Networks"
date: 2017-11-17 08:43:42
categories: arXiv_CV
tags: arXiv_CV CNN Optimization
author: Xuanyi Dong, Guoliang Kang, Kun Zhan, Yi Yang
mathjax: true
---

* content
{:toc}

##### Abstract
For most state-of-the-art architectures, Rectified Linear Unit (ReLU) becomes a standard component accompanied with each layer. Although ReLU can ease the network training to an extent, the character of blocking negative values may suppress the propagation of useful information and leads to the difficulty of optimizing very deep Convolutional Neural Networks (CNNs). Moreover, stacking layers with nonlinear activations is hard to approximate the intrinsic linear transformations between feature representations. In this paper, we investigate the effect of erasing ReLUs of certain layers and apply it to various representative architectures following deterministic rules. It can ease the optimization and improve the generalization performance for very deep CNN models. We find two key factors being essential to the performance improvement: 1) the location where ReLU should be erased inside the basic module; 2) the proportion of basic modules to erase ReLU; We show that erasing the last ReLU layer of all basic modules in a network usually yields improved performance. In experiments, our approach successfully improves the performance of various representative architectures, and we report the improved results on SVHN, CIFAR-10/100, and ImageNet. Moreover, we achieve competitive single-model performance on CIFAR-100 with 16.53% error rate compared to state-of-the-art.

##### Abstract (translated by Google)
对于大多数最先进的体系结构，整流线性单元（ReLU）成为每层的标准组件。虽然ReLU可以在一定程度上缓解网络训练，但阻塞负值的特性可能会抑制有用信息的传播，并导致优化非常深的卷积神经网络（CNN）的难度。此外，具有非线性激活的叠加层很难逼近特征表示之间的内在线性变换。在本文中，我们研究了删除特定层的ReLU的效果，并将其应用于各种代表性架构，遵循确定性规则。它可以缓解CNN模型的优化并提高泛化性能。我们发现两个关键因素对于性能提升是至关重要的：1）在基本模块内部ReLU应该被擦除的位置; 2）基本模块擦除ReLU的比例;我们显示擦除网络中所有基本模块的最后一个ReLU层通常会提高性能。在实验中，我们的方法成功地提高了各种代表性体系结构的性能，并且我们报告了在SVHN，CIFAR-10/100和ImageNet上的改进结果。此外，我们在CIFAR-100上实现了具有竞争力的单模型性能，与最先进的技术相比，错误率为16.53％。

##### URL
[https://arxiv.org/abs/1709.07634](https://arxiv.org/abs/1709.07634)

##### PDF
[https://arxiv.org/pdf/1709.07634](https://arxiv.org/pdf/1709.07634)

