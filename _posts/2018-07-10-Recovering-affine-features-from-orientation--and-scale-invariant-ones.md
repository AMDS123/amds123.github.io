---
layout: post
title: "Recovering affine features from orientation- and scale-invariant ones"
date: 2018-07-10 07:34:05
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Daniel Barath
mathjax: true
---

* content
{:toc}

##### Abstract
An approach is proposed for recovering affine correspondences (ACs) from orientation- and scale-invariant, e.g. SIFT, features. The method calculates the affine parameters consistent with a pre-estimated epipolar geometry from the point coordinates and the scales and rotations which the feature detector obtains. The closed-form solution is given as the roots of a quadratic polynomial equation, thus having two possible real candidates and fast procedure, i.e. &lt;1 millisecond. It is shown, as a possible application, that using the proposed algorithm allows us to estimate a homography for every single correspondence independently. It is validated both in our synthetic environment and on publicly available real world datasets, that the proposed technique leads to accurate ACs. Also, the estimated homographies have similar accuracy to what the state-of-the-art methods obtain, but due to requiring only a single correspondence, the robust estimation, e.g. by locally optimized RANSAC, is an order of magnitude faster.

##### Abstract (translated by Google)
提出了一种从方向和尺度不变的恢复仿射对应（AC）的方法，例如， SIFT，功能。该方法根据点坐标以及特征检测器获得的标度和旋转来计算与预估的极线几何一致的仿射参数。封闭形式的解作为二次多项式方程的根，因此具有两个可能的实际候选和快速过程，即<1毫秒。作为可能的应用，示出了使用所提出的算法允许我们独立地估计每个单独对应的单应性。它在我们的合成环境和公开可用的现实世界数据集中得到验证，所提出的技术可以产生准确的AC。此外，估计的单应性具有与现有技术方法获得的相似的精确度，但是由于仅需要单个对应，所以稳健估计，例如，通过本地优化的RANSAC，速度提高了一个数量级。

##### URL
[http://arxiv.org/abs/1807.03503](http://arxiv.org/abs/1807.03503)

##### PDF
[http://arxiv.org/pdf/1807.03503](http://arxiv.org/pdf/1807.03503)

