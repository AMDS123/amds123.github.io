---
layout: post
title: "^2 CO: Deep Depth Colorization"
date: 2017-12-26 22:04:47
categories: arXiv_CV
tags: arXiv_CV Knowledge Transfer_Learning Recognition
author: F. M. Carlucci, P. Russo, B. Caputo
mathjax: true
---

* content
{:toc}

##### Abstract
The ability to classify objects is fundamental for robots. Besides knowledge about their visual appearance, captured by the RGB channel, robots heavily need also depth information to make sense of the world. While the use of deep networks on RGB robot images has benefited from the plethora of results obtained on databases like ImageNet, using convnets on depth images requires mapping them into three dimensional channels. This transfer learning procedure makes them processable by pre-trained deep architectures. Current mappings are based on heuristic assumptions over preprocessing steps and on what depth properties should be most preserved, resulting often in cumbersome data visualizations, and in sub-optimal performance in terms of generality and recognition results. Here we take an alternative route and we attempt instead to learn an optimal colorization mapping for any given pre-trained architecture, using as training data a reference RGB-D database. We propose a deep network architecture, exploiting the residual paradigm, that learns how to map depth data to three channel images. A qualitative analysis of the images obtained with this approach clearly indicates that learning the optimal mapping preserves the richness of depth information better than current hand-crafted approaches. Experiments on the Washington, JHUIT-50 and BigBIRD public benchmark databases, using CaffeNet, VGG16, GoogleNet, and ResNet50 clearly showcase the power of our approach, with gains in performance of up to 16% compared to state of the art competitors on the depth channel only, leading to top performances when dealing with RGB-D data

##### Abstract (translated by Google)
分类对象的能力是机器人的基础。除了关于RGB通道捕获的视觉外观的知识之外，机器人还需要深度信息来理解世界。虽然在RGB机器人图像上使用深度网络已经从像ImageNet这样的数据库获得的大量结果中受益，但是使用深度图像上的网格需要将它们映射到三维通道。这种转换学习过程使得他们可以通过预先训练的深层体系结构进行处理。当前的映射基于预处理步骤的启发式假设以及什么样的深度属性应该保存得最多，从而导致繁琐的数据可视化，以及在通用性和识别结果方面的次优性能。在这里，我们采取另一种路线，我们试图学习任何给定的预先训练的架构的最佳着色映射，使用作为参考RGB-D数据库的训练数据。我们提出了深度网络架构，利用剩余范式，学习如何将深度数据映射到三个通道图像。对使用这种方法获得的图像进行定性分析清楚地表明，学习最优映射比当前手工制作的方法更好地保留了深度信息的丰富性。在华盛顿，JHUIT-50和BigBIRD公共基准数据库上使用CaffeNet，VGG16，GoogleNet和ResNet50进行的实验清楚地展示了我们的方法的强大性能，与最先进的竞争对手相比，性能提高高达16％只有通道，导致在处理RGB-D数据时表现出色

##### URL
[http://arxiv.org/abs/1703.10881](http://arxiv.org/abs/1703.10881)

##### PDF
[http://arxiv.org/pdf/1703.10881](http://arxiv.org/pdf/1703.10881)

