---
layout: post
title: "Network Decoupling: From Regular to Depthwise Separable Convolutions"
date: 2018-08-16 14:39:10
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Classification Detection Relation
author: Jianbo Guo, Yuxi Li, Weiyao Lin, Yurong Chen, Jianguo Li
mathjax: true
---

* content
{:toc}

##### Abstract
Depthwise separable convolution has shown great efficiency in network design, but requires time-consuming training procedure with full training-set available. This paper first analyzes the mathematical relationship between regular convolutions and depthwise separable convolutions, and proves that the former one could be approximated with the latter one in closed form. We show depthwise separable convolutions are principal components of regular convolutions. And then we propose network decoupling (ND), a training-free method to accelerate convolutional neural networks (CNNs) by transferring pre-trained CNN models into the MobileNet-like depthwise separable convolution structure, with a promising speedup yet negligible accuracy loss. We further verify through experiments that the proposed method is orthogonal to other training-free methods like channel decomposition, spatial decomposition, etc. Combining the proposed method with them will bring even larger CNN speedup. For instance, ND itself achieves about 2X speedup for the widely used VGG16, and combined with other methods, it reaches 3.7X speedup with graceful accuracy degradation. We demonstrate that ND is widely applicable to classification networks like ResNet, and object detection network like SSD300.

##### Abstract (translated by Google)
深度可分离卷积在网络设计中表现出很高的效率，但需要耗时的训练程序和完整的训练集。本文首先分析了规则卷积与深度可分卷积之间的数学关系，并证明前者可以用封闭形式近似。我们显示深度可分离卷积是常规卷积的主要成分。然后我们提出网络解耦（ND），这是一种无训练方法，通过将预先训练的CNN模型转换为类似MobileNet的深度可分离卷积结构来加速卷积神经网络（CNN），具有良好的加速但可忽略不计的精度损失。我们通过实验进一步验证了所提出的方法与其他无训练方法正交，如信道分解，空间分解等。将所提出的方法与它们相结合将带来更大的CNN加速。例如，对于广泛使用的VGG16，ND本身可以实现大约2倍的加速，并且与其他方法相结合，它可以达到3.7倍的加速，并且具有优雅的精度降低。我们证明ND广泛适用于ResNet等分类网络和SSD300等对象检测网络。

##### URL
[http://arxiv.org/abs/1808.05517](http://arxiv.org/abs/1808.05517)

##### PDF
[http://arxiv.org/pdf/1808.05517](http://arxiv.org/pdf/1808.05517)

