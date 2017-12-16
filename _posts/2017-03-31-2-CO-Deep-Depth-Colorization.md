---
layout: post
title: "^2 CO: Deep Depth Colorization"
date: 2017-03-31 12:30:30
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: F. M. Carlucci, P. Russo, S. M. Baharlou, B. Caputo
mathjax: true
---

* content
{:toc}

##### Abstract
Object recognition on depth images using convolutional neural networks requires mapping the data collected with depth sensors into three dimensional channels. This makes them processable by deep architectures, pre-trained over large scale RGB databases like ImageNet. Current mappings are based on heuristic assumptions over what depth properties should be most preserved, resulting often in cumbersome data visualizations, and likely in sub-optimal recognition results. Here we take an alternative route and we attempt instead to \emph{learn} an optimal colorization mapping for any given pre-trained architecture, using as training data a reference RGB-D database. We propose a deep network architecture, exploiting the residual paradigm, that learns how to map depth data to three channel images from a reference database. A qualitative analysis of the images obtained with this approach clearly indicates that learning the optimal mapping for depth data preserves the richness of depth information much better than hand-crafted approaches currently in use. Experiments on the Washington, JHUIT-50 and BigBIRD public benchmark databases, using AlexNet, VGG-16, GoogleNet, ResNet and SqueezeNet, clearly showcase the power of our approach, with gains in performance of up to $17\%$ compared to the state of the art.

##### Abstract (translated by Google)
使用卷积神经网络对深度图像进行物体识别需要将采集的深度传感器数据映射到三维通道。这使得它们可以通过深度架构进行处理，并在大型RGB数据库（如ImageNet）上进行预先训练。当前的映射基于启发式的假设，即什么样的深度属性应该被保留最多，导致繁琐的数据可视化，并可能导致次优识别结果。在这里，我们采用另一种路线，我们试图用任何给定的预先训练的架构\ emph {学习}一个最佳的着色映射，使用一个参考RGB-D数据库作为训练数据。我们提出了一个深度网络架构，利用剩余范式，学习如何将深度数据映射到来自参考数据库的三个通道图像。通过这种方法获得的图像的定性分析清楚地表明，学习深度数据的最佳映射比当前使用的手工方法更好地保存了深度信息的丰富性。使用AlexNet，VGG-16，GoogleNet，ResNet和SqueezeNet在华盛顿JHUIT-50和BigBIRD公共基准数据库上进行的实验清楚地展示了我们的方法的强大功能，与州政府相比，性能高达$ 17 \％$的艺术。

##### URL
[https://arxiv.org/abs/1703.10881](https://arxiv.org/abs/1703.10881)

##### PDF
[https://arxiv.org/pdf/1703.10881](https://arxiv.org/pdf/1703.10881)

