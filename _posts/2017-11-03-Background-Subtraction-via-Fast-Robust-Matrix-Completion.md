---
layout: post
title: "Background Subtraction via Fast Robust Matrix Completion"
date: 2017-11-03 15:55:49
categories: arXiv_CV
tags: arXiv_CV Face Optimization
author: Behnaz Rezaei, Sarah Ostadabbas
mathjax: true
---

* content
{:toc}

##### Abstract
Background subtraction is the primary task of the majority of video inspection systems. The most important part of the background subtraction which is common among different algorithms is background modeling. In this regard, our paper addresses the problem of background modeling in a computationally efficient way, which is important for current eruption of "big data" processing coming from high resolution multi-channel videos. Our model is based on the assumption that background in natural images lies on a low-dimensional subspace. We formulated and solved this problem in a low-rank matrix completion framework. In modeling the background, we benefited from the in-face extended Frank-Wolfe algorithm for solving a defined convex optimization problem. We evaluated our fast robust matrix completion (fRMC) method on both background models challenge (BMC) and Stuttgart artificial background subtraction (SABS) datasets. The results were compared with the robust principle component analysis (RPCA) and low-rank robust matrix completion (RMC) methods, both solved by inexact augmented Lagrangian multiplier (IALM). The results showed faster computation, at least twice as when IALM solver is used, while having a comparable accuracy even better in some challenges, in subtracting the backgrounds in order to detect moving objects in the scene.

##### Abstract (translated by Google)
背景扣除是大多数视频检查系统的主要任务。不同算法中常见的背景减法最重要的部分是背景建模。在这方面，我们的论文以计算有效的方式解决了背景建模问题，这对于当前高分辨率多通道视频处理的“大数据”处理是重要的。我们的模型是基于这样的假设：自然图像中的背景位于低维子空间上。我们在一个低秩矩阵完成框架中制定并解决了这个问题。在对背景进行建模时，我们受益于面内扩展的Frank-Wolfe算法，用于求解定义的凸优化问题。我们在背景模型挑战（BMC）和斯图加特人工背景减除（SABS）数据集上评估了我们的快速稳健矩阵完成（fRMC）方法。将结果与鲁棒主成分分析（RPCA）和低秩鲁棒矩阵完成（RMC）方法进行比较，两者均由不精确的增广拉格朗日乘子（IALM）求解。结果显示计算速度更快，至少是使用IALM求解器时的两倍，而在一些挑战中具有相当的准确度甚至更好，减去背景以检测场景中的移动物体。

##### URL
[https://arxiv.org/abs/1711.01218](https://arxiv.org/abs/1711.01218)

##### PDF
[https://arxiv.org/pdf/1711.01218](https://arxiv.org/pdf/1711.01218)

