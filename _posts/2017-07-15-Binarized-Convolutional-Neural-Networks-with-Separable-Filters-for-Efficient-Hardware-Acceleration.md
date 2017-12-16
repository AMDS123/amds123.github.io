---
layout: post
title: "Binarized Convolutional Neural Networks with Separable Filters for Efficient Hardware Acceleration"
date: 2017-07-15 06:17:07
categories: arXiv_CV
tags: arXiv_CV CNN
author: Jeng-Hau Lin, Tianwei Xing, Ritchie Zhao, Zhiru Zhang, Mani Srivastava, Zhuowen Tu, Rajesh K. Gupta
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art convolutional neural networks are enormously costly in both compute and memory, demanding massively parallel GPUs for execution. Such networks strain the computational capabilities and energy available to embedded and mobile processing platforms, restricting their use in many important applications. In this paper, we push the boundaries of hardware-effective CNN design by proposing BCNN with Separable Filters (BCNNw/SF), which applies Singular Value Decomposition (SVD) on BCNN kernels to further reduce computational and storage complexity. To enable its implementation, we provide a closed form of the gradient over SVD to calculate the exact gradient with respect to every binarized weight in backward propagation. We verify BCNNw/SF on the MNIST, CIFAR-10, and SVHN datasets, and implement an accelerator for CIFAR-10 on FPGA hardware. Our BCNNw/SF accelerator realizes memory savings of 17% and execution time reduction of 31.3% compared to BCNN with only minor accuracy sacrifices.

##### Abstract (translated by Google)
最先进的卷积神经网络在计算和内存方面的成本非常高，要求大规模并行GPU执行。这样的网络将嵌入式和移动处理平台的计算能力和能量压缩，限制了它们在许多重要应用中的使用。在本文中，我们通过提出带有可分离滤波器（BCNNw / SF）的BCNN，在BCNN内核上应用奇异值分解（SVD）来进一步降低计算和存储的复杂度，从而推进硬件有效的CNN设计。为了实现它的实现，我们提供了SVD梯度的闭合形式，以计算在向后传播中关于每个二进制权重的精确梯度。我们在MNIST，CIFAR-10和SVHN数据集上验证了BCNNw / SF，并在FPGA硬件上实现了CIFAR-10的加速器。与BCNN相比，我们的BCNNw / SF加速器实现了17％的内存节省和31.3％的执行时间，只需要很小的精度牺牲。

##### URL
[https://arxiv.org/abs/1707.04693](https://arxiv.org/abs/1707.04693)

##### PDF
[https://arxiv.org/pdf/1707.04693](https://arxiv.org/pdf/1707.04693)

