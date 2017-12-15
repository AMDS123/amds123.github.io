---
layout: post
title: "Deeper Depth Prediction with Fully Convolutional Residual Networks"
date: 2016-09-19 09:40:59
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Prediction
author: Iro Laina, Christian Rupprecht, Vasileios Belagiannis, Federico Tombari, Nassir Navab
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of estimating the depth map of a scene given a single RGB image. We propose a fully convolutional architecture, encompassing residual learning, to model the ambiguous mapping between monocular images and depth maps. In order to improve the output resolution, we present a novel way to efficiently learn feature map up-sampling within the network. For optimization, we introduce the reverse Huber loss that is particularly suited for the task at hand and driven by the value distributions commonly present in depth maps. Our model is composed of a single architecture that is trained end-to-end and does not rely on post-processing techniques, such as CRFs or other additional refinement steps. As a result, it runs in real-time on images or videos. In the evaluation, we show that the proposed model contains fewer parameters and requires fewer training data than the current state of the art, while outperforming all approaches on depth estimation. Code and models are publicly available.

##### Abstract (translated by Google)
本文讨论了在给定单个RGB图像的情况下估计场景的深度图的问题。我们提出了一个完全的卷积结构，包括残留学习，以模拟单目图像和深度图之间的模糊映射。为了提高输出分辨率，本文提出了一种有效学习网络内特征向上采样的新方法。为了优化，我们引入了相反的Huber损失，它特别适合于手头的任务，并且由深度图中常见的值分布驱动。我们的模型由一个端到端的训练单一体系结构组成，不依赖于后置处理技术，如CRF或其他额外的细化步骤。因此，它可以在图像或视频上实时运行。在评估中，我们表明，提出的模型包含更少的参数，需要更少的培训数据比目前的技术状态，而超越深度估计的所有方法。代码和模型是公开的。

##### URL
[https://arxiv.org/abs/1606.00373](https://arxiv.org/abs/1606.00373)

##### PDF
[https://arxiv.org/pdf/1606.00373](https://arxiv.org/pdf/1606.00373)

