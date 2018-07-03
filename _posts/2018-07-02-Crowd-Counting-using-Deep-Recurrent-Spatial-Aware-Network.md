---
layout: post
title: "Crowd Counting using Deep Recurrent Spatial-Aware Network"
date: 2018-07-02 11:21:27
categories: arXiv_CV
tags: arXiv_CV Attention
author: Lingbo Liu, Hongjun Wang, Guanbin Li, Wanli Ouyang, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Crowd counting from unconstrained scene images is a crucial task in many real-world applications like urban surveillance and management, but it is greatly challenged by the camera's perspective that causes huge appearance variations in people's scales and rotations. Conventional methods address such challenges by resorting to fixed multi-scale architectures that are often unable to cover the largely varied scales while ignoring the rotation variations. In this paper, we propose a unified neural network framework, named Deep Recurrent Spatial-Aware Network, which adaptively addresses the two issues in a learnable spatial transform module with a region-wise refinement process. Specifically, our framework incorporates a Recurrent Spatial-Aware Refinement (RSAR) module iteratively conducting two components: i) a Spatial Transformer Network that dynamically locates an attentional region from the crowd density map and transforms it to the suitable scale and rotation for optimal crowd estimation; ii) a Local Refinement Network that refines the density map of the attended region with residual learning. Extensive experiments on four challenging benchmarks show the effectiveness of our approach. Specifically, comparing with the existing best-performing methods, we achieve an improvement of 12% on the largest dataset WorldExpo'10 and 22.8% on the most challenging dataset UCF_CC_50.

##### Abstract (translated by Google)
从无约束的场景图像中计算人群是许多现实世界应用中的一项重要任务，例如城市监控和管理，但是相机的视角极大地挑战了人们的尺度和旋转造成巨大的外观变化。传统方法通过采用固定的多尺度架构来解决这些挑战，这些架构通常无法覆盖很大程度上不同的尺度而忽略了旋转变化。在本文中，我们提出了一个统一的神经网络框架，名为Deep Recurrent Spatial-Aware Network，它自适应地解决了可学习的空间变换模块中的两个问题，并采用了区域精化过程。具体来说，我们的框架结合了循环空间感知细化（RSAR）模块，迭代地执行两个组件：i）空间变换器网络，从人群密度图动态定位注意区域并将其转换为适当的比例和旋转，以实现最佳人群估计; ii）局部细化网络，其利用剩余学习来细化所关注区域的密度图。对四个具有挑战性的基准测试的广泛实验表明了我们方法的有效性。具体而言，与现有的最佳表现方法相比，我们在最大的数据集WorldExpo'10上实现了12％的提升，在最具挑战性的数据集UCF_CC_50上实现了22.8％的提升。

##### URL
[http://arxiv.org/abs/1807.00601](http://arxiv.org/abs/1807.00601)

##### PDF
[http://arxiv.org/pdf/1807.00601](http://arxiv.org/pdf/1807.00601)

