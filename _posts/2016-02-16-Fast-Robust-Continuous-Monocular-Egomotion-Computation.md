---
layout: post
title: "Fast, Robust, Continuous Monocular Egomotion Computation"
date: 2016-02-16 02:18:04
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Andrew Jaegle, Stephen Phillips, Kostas Daniilidis
mathjax: true
---

* content
{:toc}

##### Abstract
We propose robust methods for estimating camera egomotion in noisy, real-world monocular image sequences in the general case of unknown observer rotation and translation with two views and a small baseline. This is a difficult problem because of the nonconvex cost function of the perspective camera motion equation and because of non-Gaussian noise arising from noisy optical flow estimates and scene non-rigidity. To address this problem, we introduce the expected residual likelihood method (ERL), which estimates confidence weights for noisy optical flow data using likelihood distributions of the residuals of the flow field under a range of counterfactual model parameters. We show that ERL is effective at identifying outliers and recovering appropriate confidence weights in many settings. We compare ERL to a novel formulation of the perspective camera motion equation using a lifted kernel, a recently proposed optimization framework for joint parameter and confidence weight estimation with good empirical properties. We incorporate these strategies into a motion estimation pipeline that avoids falling into local minima. We find that ERL outperforms the lifted kernel method and baseline monocular egomotion estimation strategies on the challenging KITTI dataset, while adding almost no runtime cost over baseline egomotion methods.

##### Abstract (translated by Google)
我们提出了鲁棒的方法来估计在嘈杂，真实世界的单眼图像序列中的摄像机运动，在一般情况下未知的观察者旋转和翻译与两个视图和一个小基线。由于视角摄像机运动方程的非凸凸成本函数和由于噪声光流估计和场景非刚性引起的非高斯噪声，这是一个难题。为了解决这个问题，我们引入了期望的残差似然法（ERL），其在一系列反事实模型参数下使用流场残差的似然分布来估计噪声光流数据的置信度权重。我们证明ERL在识别异常值和在许多设置中恢复适当的置信度是有效的。我们将ERL与使用提升核的透视相机运动方程的新颖公式相比较，最近提出了用于具有良好经验性质的联合参数和置信度权重估计的优化框架。我们将这些策略纳入运动估计管道，避免陷入局部最小值。我们发现ERL在具有挑战性的KITTI数据集上胜过提升的内核方法和基线单眼运动估计策略，而几乎不增加基线自运动方法的运行时间成本。

##### URL
[https://arxiv.org/abs/1602.04886](https://arxiv.org/abs/1602.04886)

##### PDF
[https://arxiv.org/pdf/1602.04886](https://arxiv.org/pdf/1602.04886)

