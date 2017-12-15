---
layout: post
title: "Tracking with multi-level features"
date: 2016-07-25 15:07:45
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking Detection
author: Roberto Henschel, Laura Leal-Taixé, Bodo Rosenhahn, Konrad Schindler
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel formulation of the multiple object tracking problem which integrates low and mid-level features. In particular, we formulate the tracking problem as a quadratic program coupling detections and dense point trajectories. Due to the computational complexity of the initial QP, we propose an approximation by two auxiliary problems, a temporal and spatial association, where the temporal subproblem can be efficiently solved by a linear program and the spatial association by a clustering algorithm. The objective function of the QP is used in order to find the optimal number of clusters, where each cluster ideally represents one person. Evaluation is provided for multiple scenarios, showing the superiority of our method with respect to classic tracking-by-detection methods and also other methods that greedily integrate low-level features.

##### Abstract (translated by Google)
我们提出了一个综合了中低端特征的多目标跟踪问题的新颖表达式。具体而言，我们将跟踪问题作为二次程序耦合检测和密集点轨迹来制定。由于初始QP的计算复杂性，我们提出了两个辅助问题的近似，即时间和空间关联，其中时间子问题可以通过线性规划有效地解决，并且通过聚类算法的空间关联。使用QP的目标函数是为了找到最佳数量的聚类，其中每个聚类理想地代表一个人。针对多种情况提供了评估，显示了我们的方法在经典的逐个检测方法方面的优越性以及贪婪地集成低级特征的其他方法。

##### URL
[https://arxiv.org/abs/1607.07304](https://arxiv.org/abs/1607.07304)

##### PDF
[https://arxiv.org/pdf/1607.07304](https://arxiv.org/pdf/1607.07304)

