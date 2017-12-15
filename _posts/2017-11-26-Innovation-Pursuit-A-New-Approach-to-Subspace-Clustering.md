---
layout: post
title: "Innovation Pursuit: A New Approach to Subspace Clustering"
date: 2017-11-26 15:24:33
categories: arXiv_CV
tags: arXiv_CV Segmentation Face Optimization
author: Mostafa Rahmani, George Atia
mathjax: true
---

* content
{:toc}

##### Abstract
In subspace clustering, a group of data points belonging to a union of subspaces are assigned membership to their respective subspaces. This paper presents a new approach dubbed Innovation Pursuit (iPursuit) to the problem of subspace clustering using a new geometrical idea whereby subspaces are identified based on their relative novelties. We present two frameworks in which the idea of innovation pursuit is used to distinguish the subspaces. Underlying the first framework is an iterative method that finds the subspaces consecutively by solving a series of simple linear optimization problems, each searching for a direction of innovation in the span of the data potentially orthogonal to all subspaces except for the one to be identified in one step of the algorithm. A detailed mathematical analysis is provided establishing sufficient conditions for iPursuit to correctly cluster the data. The proposed approach can provably yield exact clustering even when the subspaces have significant intersections. It is shown that the complexity of the iterative approach scales only linearly in the number of data points and subspaces, and quadratically in the dimension of the subspaces. The second framework integrates iPursuit with spectral clustering to yield a new variant of spectral-clustering-based algorithms. The numerical simulations with both real and synthetic data demonstrate that iPursuit can often outperform the state-of-the-art subspace clustering algorithms, more so for subspaces with significant intersections, and that it significantly improves the state-of-the-art result for subspace-segmentation-based face clustering.

##### Abstract (translated by Google)
在子空间聚类中，属于子空间联合的一组数据点被分配给其各自子空间的成员资格。本文提出了一种新的方法，称为创新追求（iPursuit）子空间聚类问题使用一个新的几何思想，其中子空间是基于其相对的新奇鉴定。我们提出了两个框架，其中使用创新追求的概念来区分子空间。第一个框架的基础是一个迭代的方法，通过求解一系列简单的线性优化问题来连续地找到子空间，每个子空间在可能与所有子空间正交的数据范围内寻找创新的方向，除了要在算法的一步。提供了详细的数学分析，为iPursuit正确聚类数据建立了足够的条件。所提出的方法甚至在子空间具有显着的交点时可以证明产生精确的聚类。结果表明，迭代方法的复杂度仅在数据点和子空间的数量上线性缩放，而在子空间的维度上则是二次的。第二个框架将iPursuit与谱聚类相结合，以产生基于谱聚类算法的新变体。通过真实数据和合成数据进行的数值模拟表明，iPursuit常常可以胜过最先进的子空间聚类算法，对于具有显着交叉点的子空间，情况更是如此，并且显着提高了最先进的结果基于子空间分割的人脸聚类。

##### URL
[https://arxiv.org/abs/1512.00907](https://arxiv.org/abs/1512.00907)

##### PDF
[https://arxiv.org/pdf/1512.00907](https://arxiv.org/pdf/1512.00907)

