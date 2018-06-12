---
layout: post
title: "Capacity Releasing Diffusion for Speed and Locality"
date: 2018-06-10 08:58:07
categories: arXiv_AI
tags: arXiv_AI
author: Di Wang, Kimon Fountoulakis, Monika Henzinger, Michael W. Mahoney, Satish Rao
mathjax: true
---

* content
{:toc}

##### Abstract
Diffusions and related random walk procedures are of central importance in many areas of machine learning, data analysis, and applied mathematics. Because they spread mass agnostically at each step in an iterative manner, they can sometimes spread mass "too aggressively," thereby failing to find the "right" clusters. We introduce a novel Capacity Releasing Diffusion (CRD) Process, which is both faster and stays more local than the classical spectral diffusion process. As an application, we use our CRD Process to develop an improved local algorithm for graph clustering. Our local graph clustering method can find local clusters in a model of clustering where one begins the CRD Process in a cluster whose vertices are connected better internally than externally by an $O(\log^2 n)$ factor, where $n$ is the number of nodes in the cluster. Thus, our CRD Process is the first local graph clustering algorithm that is not subject to the well-known quadratic Cheeger barrier. Our result requires a certain smoothness condition, which we expect to be an artifact of our analysis. Our empirical evaluation demonstrates improved results, in particular for realistic social graphs where there are moderately good---but not very good---clusters.

##### Abstract (translated by Google)
扩散和相关的随机游走过程在机器学习，数据分析和应用数学的许多领域具有核心重要性。因为它们以迭代的方式在每一步以无意义的方式散布质量，所以它们有时会“大量地传播”质量，从而无法找到“正确”的聚类。我们引入了一种新颖的容量释放扩散（CRD）过程，与传统的光谱扩散过程相比，这种过程速度更快并且保持更多局部。作为一个应用程序，我们使用我们的CRD过程为图聚类开发一种改进的局部算法。我们的本地图形聚类方法可以在聚类模型中找到局部聚类，其中一个聚类开始CRD过程，聚类的顶点在内部比内部连接好得多，外部是$ O（\ log ^ 2 n）$因子，其中$ n $是集群中的节点数量。因此，我们的CRD过程是第一个不受众所周知的二次Cheeger势垒影响的局部图聚类算法。我们的结果需要一定的平滑度条件，我们认为这是我们分析的一个人为因素。我们的实证评估显示出改进的结果，特别是对于现实社会图，其中中等程度的好 - 但不是很好 - 聚类。

##### URL
[http://arxiv.org/abs/1706.05826](http://arxiv.org/abs/1706.05826)

##### PDF
[http://arxiv.org/pdf/1706.05826](http://arxiv.org/pdf/1706.05826)

