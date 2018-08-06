---
layout: post
title: "LDSO: Direct Sparse Odometry with Loop Closure"
date: 2018-08-03 08:12:29
categories: arXiv_CV
tags: arXiv_CV Sparse Tracking Optimization Detection SLAM
author: Xiang Gao, Rui Wang, Nikolaus Demmel, Daniel Cremers
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present an extension of Direct Sparse Odometry (DSO) to a monocular visual SLAM system with loop closure detection and pose-graph optimization (LDSO). As a direct technique, DSO can utilize any image pixel with sufficient intensity gradient, which makes it robust even in featureless areas. LDSO retains this robustness, while at the same time ensuring repeatability of some of these points by favoring corner features in the tracking frontend. This repeatability allows to reliably detect loop closure candidates with a conventional feature-based bag-of-words (BoW) approach. Loop closure candidates are verified geometrically and Sim(3) relative pose constraints are estimated by jointly minimizing 2D and 3D geometric error terms. These constraints are fused with a co-visibility graph of relative poses extracted from DSO's sliding window optimization. Our evaluation on publicly available datasets demonstrates that the modified point selection strategy retains the tracking accuracy and robustness, and the integrated pose-graph optimization significantly reduces the accumulated rotation-, translation- and scale-drift, resulting in an overall performance comparable to state-of-the-art feature-based systems, even without global bundle adjustment.

##### Abstract (translated by Google)
在本文中，我们提出了直接稀疏测距（DSO）扩展到单眼视觉SLAM系统与循环闭合检测和姿势图优化（LDSO）。作为一种直接技术，DSO可以利用具有足够强度梯度的任何图像像素，这使得即使在无特征区域也能够保持稳健。 LDSO保留了这种稳健性，同时通过支持跟踪前端的角落特征来确保其中一些点的可重复性。这种可重复性允许使用传统的基于特征的词袋（BoW）方法可靠地检测闭环候选。循环闭包候选者在几何上被验证，并且通过联合最小化2D和3D几何误差项来估计Sim（3）相对姿势约束。这些约束与从DSO的滑动窗口优化中提取的相对姿势的共同可见性图融合。我们对公开数据集的评估表明，修改后的点选择策略保留了跟踪精度和鲁棒性，集成的姿势图优化显着减少了累积的旋转，平移和尺度漂移，从而使整体性能与状态相当 - 即使没有全局捆绑调整，也可以使用最先进的基于功能的系统。

##### URL
[http://arxiv.org/abs/1808.01111](http://arxiv.org/abs/1808.01111)

##### PDF
[http://arxiv.org/pdf/1808.01111](http://arxiv.org/pdf/1808.01111)

