---
layout: post
title: "SpaRTA - Tracking across occlusions via global partitioning of 3D clouds of points"
date: 2018-02-16 09:40:16
categories: arXiv_CV
tags: arXiv_CV Tracking Optimization
author: Andrea Cavagna, Stefania Melillo, Leonardo Parisi, Federico Ricci-Tersenghi
mathjax: true
---

* content
{:toc}

##### Abstract
Any 3D tracking algorithm has to deal with occlusions: multiple targets get so close to each other that the loss of their identities becomes likely. In the best case scenario, trajectories are interrupted, thus curbing the completeness of the data-set; in the worse case scenario, identity switches arise, potentially affecting in severe ways the very quality of the data. Here, we present a novel tracking method that addresses the problem of occlusions within large groups of featureless objects by means of three steps: i) it represents each target as a cloud of points in 3D; ii) once a 3D cluster corresponding to an occlusion occurs, it defines a partitioning problem by introducing a cost function that uses both attractive and repulsive spatio-temporal proximity links; iii) it minimizes the cost function through a semi-definite optimization technique specifically designed to cope with link frustration. The algorithm is independent of the specific experimental method used to collect the data. By performing tests on public data-sets, we show that the new algorithm produces a significant improvement over the state-of-the-art tracking methods, both by reducing the number of identity switches and by increasing the accuracy of the actual positions of the targets in real space.

##### Abstract (translated by Google)
任何3D跟踪算法都必须处理遮挡：多个目标彼此距离过近，以至于可能会丢失其身份。在最好的情况下，轨迹会中断，从而遏制数据集的完整性;在最糟糕的情况下，身份转换出现，可能严重影响数据的质量。在这里，我们提出了一种新颖的跟踪方法，通过三个步骤解决大群无特征物体中的遮挡问题：i）它将每个目标表示为3D中的点云; ii）一旦发生与遮挡相对应的3D群集，其通过引入使用吸引和排斥时空邻近链接的成本函数来定义分割问题; iii）通过专门设计用于应对链接挫折的半定义优化技术，使成本函数最小化。该算法独立于用于收集数据的特定实验方法。通过对公共数据集进行测试，我们发现新算法对最先进的跟踪方法产生了重大改进，这两种方法都是通过减少身份切换的数量以及提高身份验证实际位置的准确性在真实空间中的目标。

##### URL
[https://arxiv.org/abs/1802.05878](https://arxiv.org/abs/1802.05878)

##### PDF
[https://arxiv.org/pdf/1802.05878](https://arxiv.org/pdf/1802.05878)

