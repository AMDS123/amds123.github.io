---
layout: post
title: "IONet: Learning to Cure the Curse of Drift in Inertial Odometry"
date: 2018-01-30 18:29:02
categories: arXiv_CV
tags: arXiv_CV Optimization RNN
author: Changhao Chen, Xiaoxuan Lu, Andrew Markham, Niki Trigoni
mathjax: true
---

* content
{:toc}

##### Abstract
Inertial sensors play a pivotal role in indoor localization, which in turn lays the foundation for pervasive personal applications. However, low-cost inertial sensors, as commonly found in smartphones, are plagued by bias and noise, which leads to unbounded growth in error when accelerations are double integrated to obtain displacement. Small errors in state estimation propagate to make odometry virtually unusable in a matter of seconds. We propose to break the cycle of continuous integration, and instead segment inertial data into independent windows. The challenge becomes estimating the latent states of each window, such as velocity and orientation, as these are not directly observable from sensor data. We demonstrate how to formulate this as an optimization problem, and show how deep recurrent neural networks can yield highly accurate trajectories, outperforming state-of-the-art shallow techniques, on a wide range of tests and attachments. In particular, we demonstrate that IONet can generalize to estimate odometry for non-periodic motion, such as a shopping trolley or baby-stroller, an extremely challenging task for existing techniques.

##### Abstract (translated by Google)
惯性传感器在室内定位中起着举足轻重的作用，从而为普遍的个人应用奠定了基础。然而，低成本的惯性传感器，如智能手机中常见的那样，受到偏置和噪声的困扰，当加速度被双重积分以获得位移时，会导致无限的误差增长。传播状态估计中的小错误，以在几秒钟内使odometry几乎不可用。我们打算打破持续整合的循环，而将惯性数据分割成独立的窗口。挑战就是估计每个窗口的潜在状态，如速度和方向，因为这些不能直接从传感器数据中观察到。我们将演示如何将此作为一个优化问题进行阐述，并展示在多种测试和附件中，经常性神经网络如何产生高度准确的轨迹，超越最先进的浅层技术。特别是，我们证明IONet可以推广到估计非周期性运动的测量法，例如购物车或婴儿车，这对于现有技术来说是非常具有挑战性的任务。

##### URL
[https://arxiv.org/abs/1802.02209](https://arxiv.org/abs/1802.02209)

##### PDF
[https://arxiv.org/pdf/1802.02209](https://arxiv.org/pdf/1802.02209)

