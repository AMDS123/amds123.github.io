---
layout: post
title: "Sdf-GAN: Semi-supervised Depth Fusion with Multi-scale Adversarial Networks"
date: 2018-03-18 13:17:16
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Relation
author: Can Pu, Runzi Song, Nanbo Li, Robert B Fisher
mathjax: true
---

* content
{:toc}

##### Abstract
Fusing disparity maps from different algorithms to exploit their complementary advantages is still challenging. Uncertainty estimation and complex disparity relationships between neighboring pixels limit the accuracy and robustness of the existing methods and there is no common method for depth fusion of different kind of data. In this paper, we introduce a method to incorporate supplementary information (intensity, gradient constraints etc.) into a Generative Adversarial Network to better refine each input disparity value. By adopting a multi-scale strategy, the disparity relationship in the fused disparity map is a better estimate of the real distribution. The approach includes a more robust object function to avoid blurry edges, impaints invalid disparity values and requires much fewer ground data to train. The algorithm can be generalized to different kinds of depth fusion. The experiments were conducted through simulation and real data, exploring different fusion opportunities: stereo-monocular fusion from coarse input, stereo-stereo fusion from moderately accurate input, fusion from accurate binocular input and Time of Flight sensor. The experiments show the superiority of the proposed algorithm compared with the most recent algorithms on the public Scene Flow and SYNTH3 datasets. The code is available from this https URL

##### Abstract (translated by Google)
融合来自不同算法的差异图以利用它们的互补优势仍然是具有挑战性的。相邻像素之间的不确定性估计和复杂的视差关系限制了现有方法的准确性和鲁棒性，并且不存在用于不同类型数据的深度融合的常用方法。在本文中，我们介绍一种将补充信息（强度，梯度约束等）并入生成对抗网络的方法，以更好地细化每个输入差异值。通过采用多尺度策略，融合视差图中的视差关系是对实际分布的更好估计。该方法包括更强大的目标函数以避免模糊的边缘，影响无效的视差值，并且需要更少的地面数据来训练。该算法可以推广到不同类型的深度融合。通过模拟和实际数据进行实验，探索不同的融合机会：粗输入的立体 - 单眼融合，中等准确输入的立体 - 立体融合，精确双目输入的融合和飞行时间传感器。实验表明，与公共场景流和SYNTH3数据集相比，该算法与最新算法相比具有优越性。该代码可从此https URL获得

##### URL
[https://arxiv.org/abs/1803.06657](https://arxiv.org/abs/1803.06657)

##### PDF
[https://arxiv.org/pdf/1803.06657](https://arxiv.org/pdf/1803.06657)

