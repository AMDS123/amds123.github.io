---
layout: post
title: "Accelerating Very Deep Convolutional Networks for Classification and Detection"
date: 2015-11-18 06:16:59
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Optimization Classification Detection Gradient_Descent
author: Xiangyu Zhang, Jianhua Zou, Kaiming He, Jian Sun
mathjax: true
---

* content
{:toc}

##### Abstract
This paper aims to accelerate the test-time computation of convolutional neural networks (CNNs), especially very deep CNNs that have substantially impacted the computer vision community. Unlike previous methods that are designed for approximating linear filters or linear responses, our method takes the nonlinear units into account. We develop an effective solution to the resulting nonlinear optimization problem without the need of stochastic gradient descent (SGD). More importantly, while previous methods mainly focus on optimizing one or two layers, our nonlinear method enables an asymmetric reconstruction that reduces the rapidly accumulated error when multiple (e.g., >=10) layers are approximated. For the widely used very deep VGG-16 model, our method achieves a whole-model speedup of 4x with merely a 0.3% increase of top-5 error in ImageNet classification. Our 4x accelerated VGG-16 model also shows a graceful accuracy degradation for object detection when plugged into the Fast R-CNN detector.

##### Abstract (translated by Google)
本文旨在加速卷积神经网络（CNN）的测试时间计算，尤其是对计算机视觉社区有重大影响的非常深的CNN。与以前设计用于近似线性滤波器或线性响应的方法不同，我们的方法考虑了非线性单元。我们开发了一个有效的解决方案来产生非线性优化问题，而不需要随机梯度下降（SGD）。更重要的是，虽然以前的方法主要集中于优化一个或两个层，但是我们的非线性方法能够进行非对称重构，以减少在多个（例如> = 10）层近似时的快速累积误差。对于广泛使用的非常深的VGG-16模型，我们的方法实现了4倍的整体模型加速，仅增加了ImageNet分类中前5位错误的0.3％。我们的4倍加速VGG-16型号在插入快速R-CNN探测器时，也显示出对物体检测的精确度降低。

##### URL
[https://arxiv.org/abs/1505.06798](https://arxiv.org/abs/1505.06798)

##### PDF
[https://arxiv.org/pdf/1505.06798](https://arxiv.org/pdf/1505.06798)

