---
layout: post
title: "Angle constrained path to cluster multiple manifolds"
date: 2018-02-21 03:51:48
categories: arXiv_CV
tags: arXiv_CV
author: Amir Babaeian
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a method to cluster multiple intersected manifolds. The algorithm chooses several landmark nodes randomly and then checks whether there is an angle constrained path between each landmark node and every other node in the neighborhood graph. When the points lie on different manifolds with intersection they should not be connected using a smooth path, thus the angle constraint is used to prevent connecting points from one cluster to another one. The resulting algorithm is implemented as a simple variation of Dijkstras algorithm used in Isomap. However, Isomap was specifically designed for dimensionality reduction in the single-manifold setting, and in particular, can-not handle intersections. Our method is simpler than the previous proposals in the literature and performs comparably to the best methods, both on simulated and some real datasets.

##### Abstract (translated by Google)
在本文中，我们提出了一种对多个相交流形进行聚类的方法。该算法随机选取几个界标节点，然后检查每个界标节点与邻域图中每个其他节点之间是否存在角度约束路径。当点位于具有交叉点的不同流形上时，它们不应该使用平滑路径进行连接，因此角度约束用于防止从一个簇到另一个簇的连接点。得到的算法被实现为Isomap中使用的Dijkstras算法的简单变体。但是，Isomap专门设计用于降低单流形设置中的维数，特别是不能处理交点。我们的方法比文献中的先前建议更简单，并且与模拟和一些真实数据集上的最佳方法相当。

##### URL
[http://arxiv.org/abs/1802.07416](http://arxiv.org/abs/1802.07416)

##### PDF
[http://arxiv.org/pdf/1802.07416](http://arxiv.org/pdf/1802.07416)

