---
layout: post
title: "Monocular Depth Estimation with Hierarchical Fusion of Dilated CNNs and Soft-Weighted-Sum Inference"
date: 2017-08-02 06:41:50
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Inference
author: Bo Li, Yuchao Dai, Mingyi He
mathjax: true
---

* content
{:toc}

##### Abstract
Monocular depth estimation is a challenging task in complex compositions depicting multiple objects of diverse scales. Albeit the recent great progress thanks to the deep convolutional neural networks (CNNs), the state-of-the-art monocular depth estimation methods still fall short to handle such real-world challenging scenarios. In this paper, we propose a deep end-to-end learning framework to tackle these challenges, which learns the direct mapping from a color image to the corresponding depth map. First, we represent monocular depth estimation as a multi-category dense labeling task by contrast to the regression based formulation. In this way, we could build upon the recent progress in dense labeling such as semantic segmentation. Second, we fuse different side-outputs from our front-end dilated convolutional neural network in a hierarchical way to exploit the multi-scale depth cues for depth estimation, which is critical to achieve scale-aware depth estimation. Third, we propose to utilize soft-weighted-sum inference instead of the hard-max inference, transforming the discretized depth score to continuous depth value. Thus, we reduce the influence of quantization error and improve the robustness of our method. Extensive experiments on the NYU Depth V2 and KITTI datasets show the superiority of our method compared with current state-of-the-art methods. Furthermore, experiments on the NYU V2 dataset reveal that our model is able to learn the probability distribution of depth.

##### Abstract (translated by Google)
单眼深度估计在描绘多个尺度的多个对象的复杂构图中是具有挑战性的任务。尽管最近由于深度卷积神经网络（CNN）而取得了巨大的进步，但是最先进的单眼深度估计方法仍然不足以处理这种真实世界的挑战性场景。在本文中，我们提出了一个深入的端到端的学习框架来应对这些挑战，从而学习从彩色图像直接映射到相应的深度图。首先，我们将单眼深度估计表示为多类别密集标记任务，与基于回归的表述相反。这样，我们就可以建立在语义分割等密集标记方面的最新进展。其次，我们将前端膨胀卷积神经网络的不同侧面输出以分层的方式进行融合，以利用多尺度深度信息进行深度估计，这对于实现尺度感知深度估计至关重要。第三，我们建议利用软加权总和推理来代替硬最大推理，将离散深度分数转换成连续深度值。这样就减少了量化误差的影响，提高了方法的鲁棒性。在纽约大学深度V2和KITTI数据集上进行的大量实验表明，与目前最先进的方法相比，我们方法的优越性。此外，NYU V2数据集的实验表明，我们的模型能够学习深度的概率分布。

##### URL
[https://arxiv.org/abs/1708.02287](https://arxiv.org/abs/1708.02287)

##### PDF
[https://arxiv.org/pdf/1708.02287](https://arxiv.org/pdf/1708.02287)

