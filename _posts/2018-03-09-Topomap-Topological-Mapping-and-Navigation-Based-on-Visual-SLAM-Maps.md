---
layout: post
title: "Topomap: Topological Mapping and Navigation Based on Visual SLAM Maps"
date: 2018-03-09 08:57:54
categories: arXiv_RO
tags: arXiv_RO Sparse Knowledge SLAM
author: Fabian Bl&#xf6;chliger, Marius Fehr, Marcin Dymczyk, Thomas Schneider, Roland Siegwart
mathjax: true
---

* content
{:toc}

##### Abstract
Visual robot navigation within large-scale, semi-structured environments deals with various challenges such as computation intensive path planning algorithms or insufficient knowledge about traversable spaces. Moreover, many state-of-the-art navigation approaches only operate locally instead of gaining a more conceptual understanding of the planning objective. This limits the complexity of tasks a robot can accomplish and makes it harder to deal with uncertainties that are present in the context of real-time robotics applications. In this work, we present Topomap, a framework which simplifies the navigation task by providing a map to the robot which is tailored for path planning use. This novel approach transforms a sparse feature-based map from a visual Simultaneous Localization And Mapping (SLAM) system into a three-dimensional topological map. This is done in two steps. First, we extract occupancy information directly from the noisy sparse point cloud. Then, we create a set of convex free-space clusters, which are the vertices of the topological map. We show that this representation improves the efficiency of global planning, and we provide a complete derivation of our algorithm. Planning experiments on real world datasets demonstrate that we achieve similar performance as RRT* with significantly lower computation times and storage requirements. Finally, we test our algorithm on a mobile robotic platform to prove its advantages.

##### Abstract (translated by Google)
大型半结构化环境中的视觉机器人导航可处理各种挑战，例如计算密集型路径规划算法或对穿越空间的了解不足。此外，许多最先进的导航方法仅在本地运行，而不是对规划目标有更多的概念性理解。这限制了机器人可以完成的任务的复杂性，并且使得处理实时机器人应用环境中存在的不确定性变得更加困难。在这项工作中，我们介绍了Topomap，这是一个通过向机器人提供地图来简化导航任务的框架，该机器人是为路径规划而定制的。这种新颖的方法将基于稀疏特征的地图从视觉同时定位和映射（SLAM）系统转换成三维拓扑地图。这是分两步完成的。首先，我们直接从嘈杂的稀疏点云中提取出入住信息。然后，我们创建一组凸自由空间聚类，这是拓扑图的顶点。我们证明这种表示提高了全局规划的效率，并且我们提供了我们算法的完全推导。对现实世界数据集进行规划实验表明，我们实现了与RRT *类似的性能，同时显着降低了计算时间和存储需求。最后，我们在移动机器人平台上测试我们的算法以证明其优势。

##### URL
[http://arxiv.org/abs/1709.05533](http://arxiv.org/abs/1709.05533)

##### PDF
[http://arxiv.org/pdf/1709.05533](http://arxiv.org/pdf/1709.05533)

