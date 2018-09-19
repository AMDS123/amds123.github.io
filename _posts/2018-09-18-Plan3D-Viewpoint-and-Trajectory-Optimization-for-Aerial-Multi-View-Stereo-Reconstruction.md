---
layout: post
title: "Plan3D: Viewpoint and Trajectory Optimization for Aerial Multi-View Stereo Reconstruction"
date: 2018-09-18 17:43:04
categories: arXiv_CV
tags: arXiv_CV Sparse Face Optimization Quantitative
author: Benjamin Hepp, Matthias Nie&#xdf;ner, Otmar Hilliges
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a new method that efficiently computes a set of viewpoints and trajectories for high-quality 3D reconstructions in outdoor environments. Our goal is to automatically explore an unknown area, and obtain a complete 3D scan of a region of interest (e.g., a large building). Images from a commodity RGB camera, mounted on an autonomously navigated quadcopter, are fed into a multi-view stereo reconstruction pipeline that produces high-quality results but is computationally expensive. In this setting, the scanning result is constrained by the restricted flight time of quadcopters. To this end, we introduce a novel optimization strategy that respects these constraints by maximizing the information gain from sparsely-sampled view points while limiting the total travel distance of the quadcopter. At the core of our method lies a hierarchical volumetric representation that allows the algorithm to distinguish between unknown, free, and occupied space. Furthermore, our information gain based formulation leverages this representation to handle occlusions in an efficient manner. In addition to the surface geometry, we utilize the free-space information to avoid obstacles and determine collision-free flight paths. Our tool can be used to specify the region of interest and to plan trajectories. We demonstrate our method by obtaining a number of compelling 3D reconstructions, and provide a thorough quantitative evaluation showing improvement over previous state-of-the-art and regular patterns.

##### Abstract (translated by Google)
我们介绍了一种新方法，可以有效地计算一组视点和轨迹，以便在室外环境中进行高质量的3D重建。我们的目标是自动探索未知区域，并获得感兴趣区域（例如，大型建筑物）的完整3D扫描。来自商品RGB相机的图像安装在自主导航的四轴飞行器上，被馈送到多视图立体声重建管道中，该管道产生高质量的结果但是计算上昂贵。在此设置中，扫描结果受限于四轴飞行器的受限飞行时间。为此，我们引入了一种新颖的优化策略，该策略通过最大化稀疏采样视点的信息增益同时限制四轴飞行器的总行进距离来尊重这些约束。我们方法的核心是分层体积表示，允许算法区分未知空间，自由空间和占用空间。此外，我们基于信息增益的公式利用此表示以有效的方式处理遮挡。除了表面几何外，我们利用自由空间信息来避开障碍物并确定无碰撞飞行路径。我们的工具可用于指定感兴趣的区域和规划轨迹。我们通过获得许多引人注目的3D重建来展示我们的方法，并提供彻底的定量评估，显示出对先前最先进和规则模式的改进。

##### URL
[http://arxiv.org/abs/1705.09314](http://arxiv.org/abs/1705.09314)

##### PDF
[http://arxiv.org/pdf/1705.09314](http://arxiv.org/pdf/1705.09314)

