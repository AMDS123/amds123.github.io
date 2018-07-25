---
layout: post
title: "Weak in the NEES?: Auto-tuning Kalman Filters with Bayesian Optimization"
date: 2018-07-23 23:02:09
categories: arXiv_RO
tags: arXiv_RO Tracking Optimization
author: Zhaozhong Chen, Christoffer Heckman, Simon Julier, Nisar Ahmed
mathjax: true
---

* content
{:toc}

##### Abstract
Kalman filters are routinely used for many data fusion applications including navigation, tracking, and simultaneous localization and mapping problems. However, significant time and effort is frequently required to tune various Kalman filter model parameters, e.g. process noise covariance, pre-whitening filter models for non-white noise, etc. Conventional optimization techniques for tuning can get stuck in poor local minima and can be expensive to implement with real sensor data. To address these issues, a new "black box" Bayesian optimization strategy is developed for automatically tuning Kalman filters. In this approach, performance is characterized by one of two stochastic objective functions: normalized estimation error squared (NEES) when ground truth state models are available, or the normalized innovation error squared (NIS) when only sensor data is available. By intelligently sampling the parameter space to both learn and exploit a nonparametric Gaussian process surrogate function for the NEES/NIS costs, Bayesian optimization can efficiently identify multiple local minima and provide uncertainty quantification on its results.

##### Abstract (translated by Google)
卡尔曼滤波器通常用于许多数据融合应用，包括导航，跟踪和同时定位和映射问题。然而，经常需要大量的时间和精力来调整各种卡尔曼滤波器模型参数，例如，过程噪声协方差，用于非白噪声的预白化滤波器模型等。用于调谐的传统优化技术可能陷入较差的局部最小值，并且用实际传感器数据实现可能是昂贵的。为了解决这些问题，开发了一种新的“黑盒子”贝叶斯优化策略，用于自动调整卡尔曼滤波器。在这种方法中，性能的特征在于两个随机目标函数之一：当可用地面实况模型时的归一化估计误差平方（NEES），或者当仅有传感器数据可用时的归一化创新误差平方（NIS）。通过智能地对参数空间进行采样以学习和利用NEES / NIS成本的非参数高斯过程替代函数，贝叶斯优化可以有效地识别多个局部最小值并对其结果提供不确定性量化。

##### URL
[http://arxiv.org/abs/1807.08855](http://arxiv.org/abs/1807.08855)

##### PDF
[http://arxiv.org/pdf/1807.08855](http://arxiv.org/pdf/1807.08855)

