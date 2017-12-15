---
layout: post
title: "Learning to Extract Motion from Videos in Convolutional Neural Networks"
date: 2016-01-27 20:19:14
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: Damien Teney, Martial Hebert
mathjax: true
---

* content
{:toc}

##### Abstract
This paper shows how to extract dense optical flow from videos with a convolutional neural network (CNN). The proposed model constitutes a potential building block for deeper architectures to allow using motion without resorting to an external algorithm, \eg for recognition in videos. We derive our network architecture from signal processing principles to provide desired invariances to image contrast, phase and texture. We constrain weights within the network to enforce strict rotation invariance and substantially reduce the number of parameters to learn. We demonstrate end-to-end training on only 8 sequences of the Middlebury dataset, orders of magnitude less than competing CNN-based motion estimation methods, and obtain comparable performance to classical methods on the Middlebury benchmark. Importantly, our method outputs a distributed representation of motion that allows representing multiple, transparent motions, and dynamic textures. Our contributions on network design and rotation invariance offer insights nonspecific to motion estimation.

##### Abstract (translated by Google)
本文介绍了如何使用卷积神经网络（CNN）从视频中提取密集的光流。所提出的模型构成了用于更深层架构的潜在构建块，以允许使用运动而不借助于外部算法，例如用于视频中的识别。我们从信号处理原理推导出我们的网络架构，为图像对比度，相位和纹理提供所需的不变性。我们限制网络中的权重来强制执行严格的旋转不变性，并大大减少要学习的参数数量。我们只对Middlebury数据集的8个序列进行端到端的训练，比竞争的基于CNN的运动估计方法少了几个数量级，并且获得了与Middlebury基准的经典方法相当的性能。重要的是，我们的方法输出运动的分布式表示，允许表示多个透明运动和动态纹理。我们对网络设计和旋转不变性的贡献提供了对运动估计非特定的见解。

##### URL
[https://arxiv.org/abs/1601.07532](https://arxiv.org/abs/1601.07532)

##### PDF
[https://arxiv.org/pdf/1601.07532](https://arxiv.org/pdf/1601.07532)

