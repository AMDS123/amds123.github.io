---
layout: post
title: "Provable Self-Representation Based Outlier Detection in a Union of Subspaces"
date: 2017-04-12 20:45:48
categories: arXiv_CV
tags: arXiv_CV Sparse Detection
author: Chong You, Daniel P. Robinson, René Vidal
mathjax: true
---

* content
{:toc}

##### Abstract
Many computer vision tasks involve processing large amounts of data contaminated by outliers, which need to be detected and rejected. While outlier detection methods based on robust statistics have existed for decades, only recently have methods based on sparse and low-rank representation been developed along with guarantees of correct outlier detection when the inliers lie in one or more low-dimensional subspaces. This paper proposes a new outlier detection method that combines tools from sparse representation with random walks on a graph. By exploiting the property that data points can be expressed as sparse linear combinations of each other, we obtain an asymmetric affinity matrix among data points, which we use to construct a weighted directed graph. By defining a suitable Markov Chain from this graph, we establish a connection between inliers/outliers and essential/inessential states of the Markov chain, which allows us to detect outliers by using random walks. We provide a theoretical analysis that justifies the correctness of our method under geometric and connectivity assumptions. Experimental results on image databases demonstrate its superiority with respect to state-of-the-art sparse and low-rank outlier detection methods.

##### Abstract (translated by Google)
许多计算机视觉任务涉及处理大量被异常值污染的数据，这些数据需要被检测和拒绝。虽然基于鲁棒统计的异常值检测方法已经存在了几十年，但是直到最近才开发了基于稀疏和低秩表示的方法，并且当内点处于一个或多个低维子空间时，保证了正确的异常点检测。本文提出了一种新的离群点检测方法，将稀疏表示的工具与图上的随机游走相结合。通过利用数据点可以表示为稀疏线性组合的性质，我们得到了数据点之间的非对称亲和矩阵，我们用它来构造一个加权有向图。通过从这个图中定义一个合适的马尔可夫链，我们建立了马克罗夫链中的内点/外点和基本/非必要状态之间的连接，这使我们能够使用随机游走来检测离群点。我们提供了一个理论分析，证明了我们的方法在几何和连接假设下的正确性。在图像数据库上的实验结果证明了其在最先进的稀疏和低秩异常值检测方法方面的优越性。

##### URL
[https://arxiv.org/abs/1704.03925](https://arxiv.org/abs/1704.03925)

##### PDF
[https://arxiv.org/pdf/1704.03925](https://arxiv.org/pdf/1704.03925)

