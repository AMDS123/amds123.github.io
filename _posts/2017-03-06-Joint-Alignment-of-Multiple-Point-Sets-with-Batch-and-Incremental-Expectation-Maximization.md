---
layout: post
title: "Joint Alignment of Multiple Point Sets with Batch and Incremental Expectation-Maximization"
date: 2017-03-06 10:47:50
categories: arXiv_CV
tags: arXiv_CV Face
author: Georgios Evangelidis, Radu Horaud
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of registering multiple point sets. Solutions to this problem are often approximated by repeatedly solving for pairwise registration, which results in an uneven treatment of the sets forming a pair: a model set and a data set. The main drawback of this strategy is that the model set may contain noise and outliers, which negatively affects the estimation of the registration parameters. In contrast, the proposed formulation treats all the point sets on an equal footing. Indeed, all the points are drawn from a central Gaussian mixture, hence the registration is cast into a clustering problem. We formally derive batch and incremental EM algorithms that robustly estimate both the GMM parameters and the rotations and translations that optimally align the sets. Moreover, the mixture's means play the role of the registered set of points while the variances provide rich information about the contribution of each component to the alignment. We thoroughly test the proposed algorithms on simulated data and on challenging real data collected with range sensors. We compare them with several state-of-the-art algorithms, and we show their potential for surface reconstruction from depth data.

##### Abstract (translated by Google)
本文讨论了注册多个点集的问题。对这个问题的解决方案往往是通过重复求解成对配准来近似的，这导致对配对的不均匀处理形成一对：模型集合和数据集合。这种策略的主要缺点是模型集可能包含噪声和异常值，这会对登记参数的估计产生负面影响。相比之下，拟议的配方在平等的基础上处理所有的点集。事实上，所有的点都是从中心的高斯混合中提取出来的，因此，这种配准就会变成一个聚类问题。我们正式推导批量和增量EM算法，可以稳健地估计GMM参数以及旋转和平移，从而最优地对齐这些集合。而且，混合物的手段扮演着注册点集合的角色，而变化提供了丰富的关于每个组件对齐的贡献的信息。我们彻底地测试了仿真数据上提出的算法以及使用距离传感器收集的具有挑战性的实际数据我们将它们与几种最先进的算法进行比较，并从深度数据展示它们的表面重建潜力。

##### URL
[https://arxiv.org/abs/1609.01466](https://arxiv.org/abs/1609.01466)

##### PDF
[https://arxiv.org/pdf/1609.01466](https://arxiv.org/pdf/1609.01466)

