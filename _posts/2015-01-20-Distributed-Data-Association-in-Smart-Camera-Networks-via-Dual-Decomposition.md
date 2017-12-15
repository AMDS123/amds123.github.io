---
layout: post
title: "Distributed Data Association in Smart Camera Networks via Dual Decomposition"
date: 2015-01-20 10:24:31
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Jiuqing Wan, Yuting Nie, Li Liu
mathjax: true
---

* content
{:toc}

##### Abstract
One of the fundamental requirements for visual surveillance using smart camera networks is the correct association of each persons observations generated on different cameras. Recently, distributed data association that involves only local information processing on each camera node and mutual information exchanging between neighboring cameras has attracted many research interests due to its superiority in large scale applications. In this paper, we formulate the problem of data association in smart camera networks as an Integer Programming problem by introducing a set of linking variables, and propose two distributed algorithms, namely L-DD and Q-DD, to solve the Integer Programming problem using dual decomposition technique. In our algorithms, the original IP problem is decomposed into several sub-problems, which can be solved locally and efficiently on each smart camera, and then different sub-problems reach consensus on their solutions in a rigorous way by adjusting their parameters based on projected sub-gradient optimization. The proposed methods are simple and flexible, in that (i) we can incorporate any feature extraction and matching technique into our framework to measure the similarity between two observations, which is used to define the cost of each link, and (ii) we can decompose the original problem in any way as long as the resulting sub-problem can be solved independently on individual camera. We show the competitiveness of our methods in both accuracy and speed by theoretical analysis and experimental comparison with state of the art algorithms on two real data sets collected by camera networks in our campus garden and office building.

##### Abstract (translated by Google)
使用智能相机网络进行视频监控的基本要求之一是每个人在不同相机上生成的观察结果的正确关联。最近，由于其在大规模应用中的优越性，仅涉及每个相机节点上的本地信息处理和相邻相机之间的相互信息交换的分布式数据关联已经吸引了许多研究兴趣。在本文中，我们通过引入一组链接变量，将智能摄像机网络中的数据关联问题作为整数规划问题，提出了L-DD和Q-DD两种分布式算法来解决整数规划问题双重分解技术。在我们的算法中，原始IP问题被分解成几个子问题，可以在每个智能相机上本地和高效地解决，然后不同的子问题通过基于投影调整它们的参数在严格的方式上达成一致分梯度优化。所提出的方法简单而灵活，因为（i）我们可以将任何特征提取和匹配技术结合到我们的框架中以测量两个观察之间的相似性，这用于定义每个链路的成本，并且（ii）我们可以只要所产生的子问题可以在单个相机上独立解决，就可以以任何方式分解原始问题。我们通过理论分析和实验比较我们的方法在准确性和速度上的竞争力，我们的校园花园和办公楼的摄像机网络收集的两个实际数据集的最先进的算法。

##### URL
[https://arxiv.org/abs/1501.04754](https://arxiv.org/abs/1501.04754)

##### PDF
[https://arxiv.org/pdf/1501.04754](https://arxiv.org/pdf/1501.04754)

