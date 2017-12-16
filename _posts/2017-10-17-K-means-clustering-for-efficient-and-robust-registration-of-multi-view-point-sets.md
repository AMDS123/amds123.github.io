---
layout: post
title: "K-means clustering for efficient and robust registration of multi-view point sets"
date: 2017-10-17 07:52:11
categories: arXiv_CV
tags: arXiv_CV
author: Zutao Jiang, Jihua Zhu, Shanmin Pang, Yaochen Li, Jun Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Efficiency and robustness are the important performance for the registration of multi-view point sets. To address these two issues, this paper casts the multi-view registration into a clustering problem, which can be solved by the extended K-means clustering algorithm. Before the clustering, all the centroids are uniformly sampled from the initially aligned point sets involved in the multi-view registration. Then, two standard K-means steps are utilized to assign all points to one special cluster and update each clustering centroid. Subsequently, the shape comprised by all cluster centroids can be used to sequentially estimate the rigid transformation for each point set. These two standard K-means steps and the step of transformation estimation constitute the extended K-means clustering algorithm, which can achieve the clustering as well as the multi-view registration by iterations. To show its superiority, the proposed approach has tested on some public data sets and compared with the-state-of-art algorithms. Experimental results illustrate its good efficiency and robustness for the registration of multi-view point sets.

##### Abstract (translated by Google)
效率和鲁棒性是多视点点集注册的重要表现。针对这两个问题，本文将多视图注册归结为聚类问题，可以通过扩展的K均值聚类算法来解决。在聚类之前，从多视图注册中涉及的初始对齐点集合中均匀采样所有质心。然后，使用两个标准的K均值步骤将所有点分配给一个特殊的聚类，并更新每个聚类质心。随后，所有聚类质心所包含的形状都可以用来顺序估计每个点集的刚性变换。这两个标准的K均值步骤和变换估计的步骤构成了扩展的K均值聚类算法，可以通过迭代实现聚类以及多视图配准。为了显示其优越性，所提出的方法已经在一些公共数据集上进行了测试，并且与现有技术的算法进行了比较。实验结果说明了多视点点集配准的良好效率和鲁棒性。

##### URL
[https://arxiv.org/abs/1710.05193](https://arxiv.org/abs/1710.05193)

##### PDF
[https://arxiv.org/pdf/1710.05193](https://arxiv.org/pdf/1710.05193)

