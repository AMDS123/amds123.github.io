---
layout: post
title: "FastDeRain: A Novel Video Rain Streak Removal Method Using Directional Gradient Priors"
date: 2018-03-20 15:32:54
categories: arXiv_CV
tags: arXiv_CV Sparse Quantitative
author: Tai-Xiang Jiang, Ting-Zhu Huang, Xi-Le Zhao, Liang-Jian Deng, Yao Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Rain streak removal is an important issue in outdoor vision systems and has recently been investigated extensively. In this paper, we propose a novel video rain streak removal approach FastDeRain, which fully considers the discriminative characteristics of rain streaks and the clean video in the gradient domain. Specifically, on the one hand, rain streaks are sparse and smooth along the direction of the raindrops, whereas on the other hand, clean videos exhibit piecewise smoothness along the rain-perpendicular direction and continuity along the temporal direction. Theses smoothness and continuity results in the sparse distribution in the different directional gradient domain, respectively. Thus, we minimize 1) the $\ell_1$ norm to enhance the sparsity of the underlying rain streaks, 2) two $\ell_1$ norm of unidirectional Total Variation (TV) regularizers to guarantee the anisotropic spatial smoothness, and 3) an $\ell_1$ norm of the time-directional difference operator to characterize the temporal continuity. A split augmented Lagrangian shrinkage algorithm (SALSA) based algorithm is designed to solve the proposed minimization model. Experiments conducted on synthetic and real data demonstrate the effectiveness and efficiency of the proposed method. According to comprehensive quantitative performance measures, our approach outperforms other state-of-the-art methods especially on account of the running time.

##### Abstract (translated by Google)
去除雨带是户外视觉系统中的一个重要问题，最近已经进行了广泛的调查。在本文中，我们提出了一种新颖的视频雨滴去除方法FastDeRain，它充分考虑了梯度区域中雨纹和干净视频的区分特征。具体而言，一方面雨滴沿着雨滴的方向是稀疏和平滑的，而另一方面，干净的视频呈现沿垂直雨滴方向的分段光滑度和沿着时间方向的连续性。这些平滑性和连续性分别导致不同方向梯度域的稀疏分布。因此，我们将1）$ \ ell_1 $范数最小化，以增强基础雨痕的稀疏性，2）两个单向全变分（TV）正则化变换器的规范，以保证各向异性空间平滑性，以及3）$ \时间方向差分算子的范数来表征时间连续性。设计了一种基于分裂增广拉格朗日收缩算法（SALSA）的算法来解决所提出的最小化模型。对合成和实际数据进行的实验证明了所提出的方法的有效性和有效性。根据全面的量化绩效衡量标准，我们的方法胜过其他最先进的方法，尤其是考虑到运行时间。

##### URL
[http://arxiv.org/abs/1803.07487](http://arxiv.org/abs/1803.07487)

##### PDF
[http://arxiv.org/pdf/1803.07487](http://arxiv.org/pdf/1803.07487)

