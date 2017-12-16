---
layout: post
title: "Plan3D: Viewpoint and Trajectory Optimization for Aerial Multi-View Stereo Reconstruction"
date: 2017-05-25 18:13:43
categories: arXiv_CV
tags: arXiv_CV Sparse Face Optimization Classification Quantitative
author: Benjamin Hepp, Matthias Nießner, Otmar Hilliges
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a new method that efficiently computes a set of rich viewpoints and trajectories for high-quality 3D reconstructions in outdoor environments. The input images of the reconstruction are taken with a commodity RGB camera which is mounted on an autonomously navigated quadcopter, and the obtained recordings are fed into a multi-view stereo reconstruction pipeline that produces high-quality results but is computationally expensive. Our goal is to automatically explore an unknown area, and obtain a complete 3D scan of a region of interest (e.g., a large building). In this process, the scan is constraint by the restricted flight time of quadcopters and the heavy compute costs of the subsequent 3D reconstruction -- i.e., only a small number of images can be recorded and processed. To this end, we introduce a novel optimization strategy that respects these constraints by maximizing the information gain from sparsely-sampled view points while limiting the total number of captured images. The core of this strategy is based on the concept of tri-state space classification, which is common in volumetric fusion approaches, and includes labels for unknown, free, and occupied space. Our optimization leverages a hierarchical and sparse volumetric data structure that takes advantage of the implicit representation, where its main objective is to convert unknown space into known regions. In addition to the surface geometry, we utilize the free-space information to avoid obstacles and determine feasible flight paths. A simple tool can be used to specify the region of interest and to plan trajectories. We demonstrate our method by obtaining a number of compelling 3D reconstructions, and provide a thorough quantitative evaluation for our optimization strategy.

##### Abstract (translated by Google)
我们引入了一种新的方法，可以高效地计算一系列丰富的视点和轨迹，以便在户外环境中进行高质量的三维重建。重建的输入图像是通过安装在自主导航四轴飞行器上的商品RGB摄像机获取的，并且获得的记录被馈送到多视图立体声重建管线，其产生高质量的结果，但是在计算上是昂贵的。我们的目标是自动探索未知区域，并获得一个感兴趣的区域（例如，一个大型建筑物）的完整3D扫描。在这个过程中，扫描受到四轴飞行器飞行时间的限制以及后续3D重建的沉重计算成本的限制，即只能记录和处理少量的图像。为此，我们引入了一种新颖的优化策略，通过最大限度地利用稀疏采样视点的信息增益，同时限制捕获图像的总数量来尊重这些约束。这个策略的核心是基于三态空间分类的概念，这在体积融合方法中是很常见的，并且包括未知，自由和占用空间的标签。我们的优化利用了分层和稀疏的体数据结构，利用隐式表示，其主要目标是将未知空间转换为已知区域。除了表面几何外，我们利用自由空间信息来避开障碍物并确定可行的飞行路径。一个简单的工具可以用来指定感兴趣的区域并计划轨迹。我们通过获得一些引人注目的3D重建来证明我们的方法，并为我们的优化策略提供了一个彻底的定量评估。

##### URL
[https://arxiv.org/abs/1705.09314](https://arxiv.org/abs/1705.09314)

##### PDF
[https://arxiv.org/pdf/1705.09314](https://arxiv.org/pdf/1705.09314)

