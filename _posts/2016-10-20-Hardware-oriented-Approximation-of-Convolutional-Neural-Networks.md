---
layout: post
title: "Hardware-oriented Approximation of Convolutional Neural Networks"
date: 2016-10-20 15:09:39
categories: arXiv_CV
tags: arXiv_CV CNN
author: Philipp Gysel, Mohammad Motamedi, Soheil Ghiasi
mathjax: true
---

* content
{:toc}

##### Abstract
High computational complexity hinders the widespread usage of Convolutional Neural Networks (CNNs), especially in mobile devices. Hardware accelerators are arguably the most promising approach for reducing both execution time and power consumption. One of the most important steps in accelerator development is hardware-oriented model approximation. In this paper we present Ristretto, a model approximation framework that analyzes a given CNN with respect to numerical resolution used in representing weights and outputs of convolutional and fully connected layers. Ristretto can condense models by using fixed point arithmetic and representation instead of floating point. Moreover, Ristretto fine-tunes the resulting fixed point network. Given a maximum error tolerance of 1%, Ristretto can successfully condense CaffeNet and SqueezeNet to 8-bit. The code for Ristretto is available.

##### Abstract (translated by Google)
高计算复杂性阻碍了卷积神经网络（CNN）的广泛使用，特别是在移动设备中。硬件加速器可以说是减少执行时间和功耗最有前途的方法。加速器开发中最重要的步骤之一是面向硬件的模型逼近。在本文中，我们提出Ristretto，一个模型近似框架，分析一个给定的CNN的数值分辨率用于表示卷积和完全连接层的权重和输出。 Ristretto可以通过使用定点算术和表示而不是浮点来压缩模型。而且，Ristretto对所得的定点网络进行微调。给定1％的最大误差容限，Ristretto可以成功压缩CaffeNet和SqueezeNet到8位。 Ristretto的代码是可用的。

##### URL
[https://arxiv.org/abs/1604.03168](https://arxiv.org/abs/1604.03168)

##### PDF
[https://arxiv.org/pdf/1604.03168](https://arxiv.org/pdf/1604.03168)

