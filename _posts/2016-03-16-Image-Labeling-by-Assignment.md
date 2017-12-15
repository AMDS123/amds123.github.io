---
layout: post
title: "Image Labeling by Assignment"
date: 2016-03-16 21:15:49
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Freddie Åström, Stefania Petra, Bernhard Schmitzer, Christoph Schnörr
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel geometric approach to the image labeling problem. Abstracting from specific labeling applications, a general objective function is defined on a manifold of stochastic matrices, whose elements assign prior data that are given in any metric space, to observed image measurements. The corresponding Riemannian gradient flow entails a set of replicator equations, one for each data point, that are spatially coupled by geometric averaging on the manifold. Starting from uniform assignments at the barycenter as natural initialization, the flow terminates at some global maximum, each of which corresponds to an image labeling that uniquely assigns the prior data. Our geometric variational approach constitutes a smooth non-convex inner approximation of the general image labeling problem, implemented with sparse interior-point numerics in terms of parallel multiplicative updates that converge efficiently.

##### Abstract (translated by Google)
我们引入了一种新的几何方法来解决图像标注问题。从具体的标签应用中抽象出来，在随机矩阵的流形上定义了一个通用的目标函数，其元素将任何度量空间中给出的先验数据分配给观察的图像测量。相应的黎曼梯度流需要一组复制器方程，每个数据点一个，通过流形上的几何平均在空间上耦合。从重心处的统一分配作为自然初始化开始，流程在某个全局最大值处终止，每个最大值对应于唯一分配先前数据的图像标记。我们的几何变分方法构成了一般图像标记问题的平滑非凸内部逼近，用稀疏的内点数值在并行乘法更新方面实现，这些并行乘法更新有效地收敛。

##### URL
[https://arxiv.org/abs/1603.05285](https://arxiv.org/abs/1603.05285)

##### PDF
[https://arxiv.org/pdf/1603.05285](https://arxiv.org/pdf/1603.05285)

