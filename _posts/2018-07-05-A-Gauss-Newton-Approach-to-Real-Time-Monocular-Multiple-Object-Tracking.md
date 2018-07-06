---
layout: post
title: "A Gauss-Newton Approach to Real-Time Monocular Multiple Object Tracking"
date: 2018-07-05 16:56:54
categories: arXiv_CV
tags: arXiv_CV Knowledge Tracking Object_Tracking Optimization Gradient_Descent
author: Henning Tjaden, Ulrich Schwanecke, Elmar Sch&#xf6;mer, Daniel Cremers
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an algorithm for real-time 6DOF pose tracking of rigid 3D objects using a monocular RGB camera. The key idea is to derive a region-based cost function using temporally consistent local color histograms. While such region-based cost functions are commonly optimized using first-order gradient descent techniques, we systematically derive a Gauss-Newton optimization scheme which gives rise to drastically faster convergence and highly accurate and robust tracking performance. We furthermore propose a novel complex dataset dedicated for the task of monocular object pose tracking and make it publicly available to the community. To our knowledge, It is the first to address the common and important scenario in which both the camera as well as the objects are moving simultaneously in cluttered scenes. In numerous experiments - including our own proposed data set - we demonstrate that the proposed Gauss-Newton approach outperforms existing approaches, in particular in the presence of cluttered backgrounds, heterogeneous objects and partial occlusions.

##### Abstract (translated by Google)
我们提出了一种使用单目RGB相机对刚性3D物体进行实时6DOF姿态跟踪的算法。关键思想是使用时间上一致的局部颜色直方图来导出基于区域的成本函数。虽然这些基于区域的成本函数通常使用一阶梯度下降技术进行优化，但我们系统地推导出高斯 - 牛顿优化方案，该方案可以实现极快的收敛速度和高度准确且强大的跟踪性能。我们还提出了一种新颖的复杂数据集，专门用于单眼对象姿势跟踪任务，并向社区公开。据我们所知，它是第一个解决相机和物体在杂乱场景中同时移动的常见且重要的场景。在许多实验中 - 包括我们自己提出的数据集 - 我们证明了所提出的Gauss-Newton方法优于现有方法，特别是在存在杂乱背景，异质对象和部分遮挡的情况下。

##### URL
[http://arxiv.org/abs/1807.02087](http://arxiv.org/abs/1807.02087)

##### PDF
[http://arxiv.org/pdf/1807.02087](http://arxiv.org/pdf/1807.02087)

