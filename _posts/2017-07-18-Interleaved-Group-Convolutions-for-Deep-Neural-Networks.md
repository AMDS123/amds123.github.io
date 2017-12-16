---
layout: post
title: "Interleaved Group Convolutions for Deep Neural Networks"
date: 2017-07-18 07:46:45
categories: arXiv_CV
tags: arXiv_CV CNN
author: Ting Zhang, Guo-Jun Qi, Bin Xiao, Jingdong Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a simple and modularized neural network architecture, named interleaved group convolutional neural networks (IGCNets). The main point lies in a novel building block, a pair of two successive interleaved group convolutions: primary group convolution and secondary group convolution. The two group convolutions are complementary: (i) the convolution on each partition in primary group convolution is a spatial convolution, while on each partition in secondary group convolution, the convolution is a point-wise convolution; (ii) the channels in the same secondary partition come from different primary partitions. We discuss one representative advantage: Wider than a regular convolution with the number of parameters and the computation complexity preserved. We also show that regular convolutions, group convolution with summation fusion, and the Xception block are special cases of interleaved group convolutions. Empirical results over standard benchmarks, CIFAR-$10$, CIFAR-$100$, SVHN and ImageNet demonstrate that our networks are more efficient in using parameters and computation complexity with similar or higher accuracy.

##### Abstract (translated by Google)
在本文中，我们提出了一个简单的模块化神经网络架构，称为交织群卷积神经网络（IGCNets）。重点在于一个新颖的积木，一对两个连续的交错群卷积：主群卷积和次群卷积。两组卷积是互补的：（i）主组卷积中的每个分区的卷积是空间卷积，而在次组卷积中的每个分区上，卷积是逐点卷积; （ii）同一辅助分区中的信道来自不同的主分区。我们讨论一个代表性的优点：比参数数量和计算复杂度保存的正则卷积宽。我们还展示了正则卷积，带求和融合的群卷积和Xception块是交织群卷积的特例。在标准基准，CIFAR- $ 10 $，CIFAR- $ 100 $，SVHN和ImageNet上的经验结果表明，我们的网络在使用参数和计算复杂性时具有相似或更高的精度。

##### URL
[https://arxiv.org/abs/1707.02725](https://arxiv.org/abs/1707.02725)

##### PDF
[https://arxiv.org/pdf/1707.02725](https://arxiv.org/pdf/1707.02725)

