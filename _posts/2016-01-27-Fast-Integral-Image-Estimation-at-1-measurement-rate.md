---
layout: post
title: "Fast Integral Image Estimation at 1% measurement rate"
date: 2016-01-27 04:32:20
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking Quantitative
author: Kuldeep Kulkarni, Pavan Turaga
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a framework called ReFInE to directly obtain integral image estimates from a very small number of spatially multiplexed measurements of the scene without iterative reconstruction of any auxiliary image, and demonstrate their practical utility in visual object tracking. Specifically, we design measurement matrices which are tailored to facilitate extremely fast estimation of the integral image, by using a single-shot linear operation on the measured vector. Leveraging a prior model for the images, we formulate a nuclear norm minimization problem with second order conic constraints to jointly obtain the measurement matrix and the linear operator. Through qualitative and quantitative experiments, we show that high quality integral image estimates can be obtained using our framework at very low measurement rates. Further, on a standard dataset of 50 videos, we present object tracking results which are comparable to the state-of-the-art methods, even at an extremely low measurement rate of 1%.

##### Abstract (translated by Google)
我们提出了一个名为ReFInE的框架，直接从场景中非常少量的空间多路复用测量中获得积分图像估计，而不需要对任何辅助图像进行迭代重建，并展示了它们在视觉对象跟踪中的实际效用。具体来说，我们设计了测量矩阵，通过在测量的矢量上使用单次线性运算来对测量矩阵进行量身定制，以便极快地估计积分图像。利用图像的先验模型，用二阶圆锥曲线约束条件制定核范数最小化问题，共同获得测量矩阵和线性算子。通过定性和定量实验，我们表明，使用我们的框架可以在非常低的测量速率下获得高质量的积分图像估计。此外，在50个视频的标准数据集上，我们提供了与最先进的方法相媲美的目标跟踪结果，即使在1％的极低测量率下。

##### URL
[https://arxiv.org/abs/1601.07258](https://arxiv.org/abs/1601.07258)

##### PDF
[https://arxiv.org/pdf/1601.07258](https://arxiv.org/pdf/1601.07258)

