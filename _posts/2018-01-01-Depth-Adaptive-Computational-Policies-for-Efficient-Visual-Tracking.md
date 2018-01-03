---
layout: post
title: "Depth-Adaptive Computational Policies for Efficient Visual Tracking"
date: 2018-01-01 20:54:33
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Object_Tracking
author: Chris Ying, Katerina Fragkiadaki
mathjax: true
---

* content
{:toc}

##### Abstract
Current convolutional neural networks algorithms for video object tracking spend the same amount of computation for each object and video frame. However, it is harder to track an object in some frames than others, due to the varying amount of clutter, scene complexity, amount of motion, and object's distinctiveness against its background. We propose a depth-adaptive convolutional Siamese network that performs video tracking adaptively at multiple neural network depths. Parametric gating functions are trained to control the depth of the convolutional feature extractor by minimizing a joint loss of computational cost and tracking error. Our network achieves accuracy comparable to the state-of-the-art on the VOT2016 benchmark. Furthermore, our adaptive depth computation achieves higher accuracy for a given computational cost than traditional fixed-structure neural networks. The presented framework extends to other tasks that use convolutional neural networks and enables trading speed for accuracy at runtime.

##### Abstract (translated by Google)
当前用于视频对象跟踪的卷积神经网络算法对于每个对象和视频帧花费相同的计算量。然而，由于杂波的数量，景物的复杂程度，运动量以及物体与背景的区别等原因，在某些帧中跟踪物体比较难。我们提出了一个深度自适应卷积连体网络，在多个神经网络深度自适应地执行视频跟踪。通过最小化计算成本和跟踪误差的联合损失来训练参数门控函数以控制卷积特征提取器的深度。我们的网络实现了与VOT2016基准测试中的最新技术相媲美的准确性。此外，与传统的固定结构神经网络相比，我们的自适应深度计算在给定的计算成本下实现了更高的精度。提出的框架扩展到使用卷积神经网络的其他任务，并在运行时实现交易速度的准确性。

##### URL
[http://arxiv.org/abs/1801.00508](http://arxiv.org/abs/1801.00508)

##### PDF
[http://arxiv.org/pdf/1801.00508](http://arxiv.org/pdf/1801.00508)

