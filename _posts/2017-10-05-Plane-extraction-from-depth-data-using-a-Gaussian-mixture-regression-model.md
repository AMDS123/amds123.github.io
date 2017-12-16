---
layout: post
title: "Plane-extraction from depth-data using a Gaussian mixture regression model"
date: 2017-10-05 09:09:18
categories: arXiv_CV
tags: arXiv_CV Drone Embedding
author: Richard T. Marriott, Alexander Paschevich, Radu Horaud
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel algorithm for unsupervised extraction of piecewise planar models from depth-data. Among other applications, such models are a good way of enabling autonomous agents (robots, cars, drones, etc.) to effectively perceive their surroundings and to navigate in three dimensions. We propose to do this by fitting the data with a piecewise-linear Gaussian mixture regression model whose components are skewed over planes, making them flat in appearance rather than being ellipsoidal, by embedding an outlier-trimming process that is formally incorporated into the proposed expectation-maximization algorithm, and by selectively fusing contiguous, coplanar components. Part of our motivation is an attempt to estimate more accurate plane-extraction by allowing each model component to make use of all available data through probabilistic clustering. The algorithm is thoroughly evaluated against a standard benchmark and is shown to rank among the best of the existing state-of-the-art methods.

##### Abstract (translated by Google)
我们提出了一种无监督的从深度数据提取分段平面模型的新算法。在其他应用中，这样的模型是使自主代理（机器人，汽车，无人驾驶飞机等）有效地感知其周围环境并以三维方式导航的好方法。我们建议通过用分段线性高斯混合回归模型来拟合数据，其分量在平面上是倾斜的，使得它们在外观上是平坦的而不是椭圆体，通过嵌入异常值修剪过程，该过程正式地结合到所提出的期望中最大化算法，并选择性地融合连续的共面分量。我们的部分动机是试图通过允许每个模型组件通过概率聚类来利用所有可用数据来估计更准确的平面提取。该算法根据标准基准进行了全面评估，并被证明是现有最先进方法中最好的。

##### URL
[https://arxiv.org/abs/1710.01925](https://arxiv.org/abs/1710.01925)

##### PDF
[https://arxiv.org/pdf/1710.01925](https://arxiv.org/pdf/1710.01925)

