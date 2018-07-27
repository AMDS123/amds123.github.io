---
layout: post
title: "Loosely-Coupled Semi-Direct Monocular SLAM"
date: 2018-07-26 11:35:34
categories: arXiv_CV
tags: arXiv_CV Optimization SLAM
author: Seong Hun Lee, Javier Civera
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel semi-direct approach for monocular simultaneous localization and mapping (SLAM) that combines the complementary strengths of direct and feature-based methods. The proposed pipeline loosely couples direct odometry and feature-based SLAM to perform three levels of parallel optimizations: (1) photometric bundle adjustment (BA) that jointly optimizes the local structure and motion, (2) geometric BA that refines keyframe poses and associated feature map points, and (3) pose graph optimization to achieve global map consistency in the presence of loop closures. This is achieved in real-time by limiting the feature-based operations to marginalized keyframes from the direct odometry module. Exhaustive evaluation on two benchmark datasets demonstrates that our system outperforms the state-of-the-art monocular odometry and SLAM systems in terms of overall accuracy and robustness.

##### Abstract (translated by Google)
我们提出了一种新颖的半直接方法，用于单目同时定位和绘图（SLAM），它结合了直接和基于特征的方法的互补优势。拟议的管道松散地耦合直接测距和基于特征的SLAM以执行三个级别的并行优化：（1）光度束调整（BA），其共同优化局部结构和运动，（2）几何BA，其细化关键帧姿势和相关特征映射点，以及（3）姿势图优化，以在存在闭环的情况下实现全局映射一致性。这是通过将基于特征的操作限制为来自直接测距模块的边缘化关键帧来实时实现的。对两个基准数据集的详尽评估表明，我们的系统在整体精度和稳健性方面优于最先进的单眼测距和SLAM系统。

##### URL
[http://arxiv.org/abs/1807.10073](http://arxiv.org/abs/1807.10073)

##### PDF
[http://arxiv.org/pdf/1807.10073](http://arxiv.org/pdf/1807.10073)

