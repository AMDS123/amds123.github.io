---
layout: post
title: "XNOR-Net: ImageNet Classification Using Binary Convolutional Neural Networks"
date: 2016-08-02 20:59:14
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Mohammad Rastegari, Vicente Ordonez, Joseph Redmon, Ali Farhadi
mathjax: true
---

* content
{:toc}

##### Abstract
We propose two efficient approximations to standard convolutional neural networks: Binary-Weight-Networks and XNOR-Networks. In Binary-Weight-Networks, the filters are approximated with binary values resulting in 32x memory saving. In XNOR-Networks, both the filters and the input to convolutional layers are binary. XNOR-Networks approximate convolutions using primarily binary operations. This results in 58x faster convolutional operations and 32x memory savings. XNOR-Nets offer the possibility of running state-of-the-art networks on CPUs (rather than GPUs) in real-time. Our binary networks are simple, accurate, efficient, and work on challenging visual tasks. We evaluate our approach on the ImageNet classification task. The classification accuracy with a Binary-Weight-Network version of AlexNet is only 2.9% less than the full-precision AlexNet (in top-1 measure). We compare our method with recent network binarization methods, BinaryConnect and BinaryNets, and outperform these methods by large margins on ImageNet, more than 16% in top-1 accuracy.

##### Abstract (translated by Google)
我们提出了两种有效的标准卷积神经网络的近似：二进制权重网络和XNOR网络。在二进制权重网络中，滤波器近似于二进制值，从而节省了32倍的存储空间。在XNOR网络中，滤波器和卷积层的输入都是二进制的。 XNOR网络主要使用二元运算近似卷积。这使得卷积操作速度提高了58倍，节省了32倍的内存。 XNOR网络提供了在CPU（而不是GPU）上实时运行最先进网络的可能性。我们的二进制网络简单，准确，高效，并能应对具有挑战性的视觉任务。我们在ImageNet分类任务上评估我们的方法。二进制权重网络版AlexNet的分类精度仅比全精度AlexNet（前1度）低2.9％。我们将我们的方法与最近的网络二值化方法BinaryConnect和BinaryNets进行比较，并在ImageNet上大幅超越这些方法，超过了前16％的精度。

##### URL
[https://arxiv.org/abs/1603.05279](https://arxiv.org/abs/1603.05279)

##### PDF
[https://arxiv.org/pdf/1603.05279](https://arxiv.org/pdf/1603.05279)

