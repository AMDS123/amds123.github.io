---
layout: post
title: "Towards a tracking algorithm based on the clustering of spatio-temporal clouds of points"
date: 2015-11-04 11:20:51
categories: arXiv_CV
tags: arXiv_CV Tracking Optimization
author: Andrea Cavagna, Chiara Creato, Lorenzo Del Castello, Stefania Melillo, Leonardo Parisi, Massimiliano Viale
mathjax: true
---

* content
{:toc}

##### Abstract
The interest in 3D dynamical tracking is growing in fields such as robotics, biology and fluid dynamics. Recently, a major source of progress in 3D tracking has been the study of collective behaviour in biological systems, where the trajectories of individual animals moving within large and dense groups need to be reconstructed to understand the behavioural interaction rules. Experimental data in this field are generally noisy and at low spatial resolution, so that individuals appear as small featureless objects and trajectories must be retrieved by making use of epipolar information only. Moreover, optical occlusions often occur: in a multi-camera system one or more objects become indistinguishable in one view, potentially jeopardizing the conservation of identity over long-time trajectories. The most advanced 3D tracking algorithms overcome optical occlusions making use of set-cover techniques, which however have to solve NP-hard optimization problems. Moreover, current methods are not able to cope with occlusions arising from actual physical proximity of objects in 3D space. Here, we present a new method designed to work directly in 3D space and time, creating (3D+1) clouds of points representing the full spatio-temporal evolution of the moving targets. We can then use a simple connected components labeling routine, which is linear in time, to solve optical occlusions, hence lowering from NP to P the complexity of the problem. Finally, we use normalized cut spectral clustering to tackle 3D physical proximity.

##### Abstract (translated by Google)
对三维动态跟踪的兴趣在诸如机器人，生物学和流体动力学等领域日益增长。最近，三维跟踪的主要进展来源于生物系统的集体行为研究，在这个系统中，个体动物在大而密集的群体中移动的轨迹需要被重建以理解行为交互规则。在这个领域的实验数据通常是噪声和低空间分辨率，所以个人表现为小的无特征物体和轨迹必须通过使用核线信息检索只。此外，光学遮挡经常发生：在多摄像机系统中，一个或多个对象在一个视图中变得难以区分，可能会危及长时间轨迹上的身份保持。最先进的三维跟踪算法克服了利用集覆盖技术的光学遮挡，然而这些技术必须解决NP-hard优化问题。而且，目前的方法不能处理由三维空间中物体的实际物理接近引起的遮挡。在这里，我们提出了一种新的方法，设计为直接在三维空间和时间工作，创建（3D + 1）点云代表移动目标的完整时空演变。然后，我们可以使用一个简单的时间线性连通分量标记程序来解决光学遮挡问题，从而从NP到P降低问题的复杂度。最后，我们使用归一化切割谱聚类来处理3D物理接近度。

##### URL
[https://arxiv.org/abs/1511.01293](https://arxiv.org/abs/1511.01293)

##### PDF
[https://arxiv.org/pdf/1511.01293](https://arxiv.org/pdf/1511.01293)

