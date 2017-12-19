---
layout: post
title: "Iterative hypothesis testing for multi-object tracking in presence of features with variable reliability"
date: 2015-09-01 14:27:50
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking Detection
author: Amit Kumar K.C., Damien Delannay, Christophe De Vleeschouwer
mathjax: true
---

* content
{:toc}

##### Abstract
This paper assumes prior detections of multiple targets at each time instant, and uses a graph-based approach to connect those detections across time, based on their position and appearance estimates. In contrast to most earlier works in the field, our framework has been designed to exploit the appearance features, even when they are only sporadically available, or affected by a non-stationary noise, along the sequence of detections. This is done by implementing an iterative hypothesis testing strategy to progressively aggregate the detections into short trajectories, named tracklets. Specifically, each iteration considers a node, named key-node, and investigates how to link this key-node with other nodes in its neighborhood, under the assumption that the target appearance is defined by the key-node appearance estimate. This is done through shortest path computation in a temporal neighborhood of the key-node. The approach is conservative in that it only aggregates the shortest paths that are sufficiently better compared to alternative paths. It is also multi-scale in that the size of the investigated neighborhood is increased proportionally to the number of detections already aggregated into the key-node. The multi-scale nature of the process and the progressive relaxation of its conservativeness makes it both computationally efficient and effective. Experimental validations are performed extensively on a toy example, a 15 minutes long multi-view basketball dataset, and other monocular pedestrian datasets.

##### Abstract (translated by Google)
本文假定在每个时刻先检测多个目标，并且使用基于图的方法根据它们的位置和外观估计值来跨越时间来连接这些检测。与该领域大多数早期的作品相比，我们的框架被设计为利用外观特征，即使它们只是零星可用，或者受到非平稳噪声的影响，沿着检测序列。这是通过实施迭代假设检验策略逐步将检测集合成短轨迹（称为轨迹）来完成的。具体而言，每次迭代都会考虑一个名为key-node的节点，并且在假设目标外观由关键节点外观估计定义的情况下，研究如何将此key-node与其邻居中的其他节点进行链接。这是通过关键节点的时间邻域中的最短路径计算完成的。这种方法是保守的，因为它只汇集比替代路径足够好的最短路径。这也是多尺度的，被调查的邻域的大小与已经聚集到关键节点的检测的数量成比例地增加。这个过程的多尺度特性以及其保守性的逐渐放松使得它既具有计算效率又有效。实验验证广泛地在玩具实例，15分钟长的多视图篮球数据集和其他单眼人行数据集上执行。

##### URL
[https://arxiv.org/abs/1509.00313](https://arxiv.org/abs/1509.00313)

##### PDF
[https://arxiv.org/pdf/1509.00313](https://arxiv.org/pdf/1509.00313)

