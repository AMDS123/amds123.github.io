---
layout: post
title: "Data-Driven Clustering via Parameterized Lloyd's Families"
date: 2018-09-19 02:36:25
categories: arXiv_AI
tags: arXiv_AI
author: Maria-Florina Balcan, Travis Dick, Colin White
mathjax: true
---

* content
{:toc}

##### Abstract
Algorithms for clustering points in metric spaces is a long-studied area of research. Clustering has seen a multitude of work both theoretically, in understanding the approximation guarantees possible for many objective functions such as k-median and k-means clustering, and experimentally, in finding the fastest algorithms and seeding procedures for Lloyd's algorithm. The performance of a given clustering algorithm depends on the specific application at hand, and this may not be known up front. For example, a "typical instance" may vary depending on the application, and different clustering heuristics perform differently depending on the instance. 
 In this paper, we define an infinite family of algorithms generalizing Lloyd's algorithm, with one parameter controlling the the initialization procedure, and another parameter controlling the local search procedure. This family of algorithms includes the celebrated k-means++ algorithm, as well as the classic farthest-first traversal algorithm. We design efficient learning algorithms which receive samples from an application-specific distribution over clustering instances and learn a near-optimal clustering algorithm from the class. We show the best parameters vary significantly across datasets such as MNIST, CIFAR, and mixtures of Gaussians. Our learned algorithms never perform worse than k-means++, and on some datasets we see significant improvements.

##### Abstract (translated by Google)
在度量空间中聚类点的算法是一个长期研究的研究领域。从理论上讲，聚类在理解许多目标函数（如k-median和k-means聚类）可能的近似保证以及实验中找到Lloyd算法的最快算法和种子程序方面已经有了大量的工作。给定聚类算法的性能取决于手头的具体应用，这可能不是预先知道的。例如，“典型实例”可以根据应用而变化，并且不同的聚类启发式根据实例而不同地执行。
 在本文中，我们定义了一个无限的算法系列，推广了劳埃德算法，一个参数控制初始化过程，另一个参数控制局部搜索过程。这一类算法包括着名的k-means ++算法，以及经典的最先优遍历算法。我们设计了有效的学习算法，这些算法通过聚类实例从特定于应用程序的分布接收样本，并从类中学习近似最优的聚类算法。我们展示了各种数据集中最佳参数的显着差异，如MNIST，CIFAR和高斯混合。我们学到的算法从不比k-means ++表现差，在一些数据集上我们看到了显着的改进。

##### URL
[http://arxiv.org/abs/1809.06987](http://arxiv.org/abs/1809.06987)

##### PDF
[http://arxiv.org/pdf/1809.06987](http://arxiv.org/pdf/1809.06987)

