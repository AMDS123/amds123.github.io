---
layout: post
title: "Scalable Surface Reconstruction from Point Clouds with Extreme Scale and Density Diversity"
date: 2017-05-02 13:13:47
categories: arXiv_CV
tags: arXiv_CV Face Optimization
author: Christian Mostegel, Rudolf Prettenthaler, Friedrich Fraundorfer, Horst Bischof
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present a scalable approach for robustly computing a 3D surface mesh from multi-scale multi-view stereo point clouds that can handle extreme jumps of point density (in our experiments three orders of magnitude). The backbone of our approach is a combination of octree data partitioning, local Delaunay tetrahedralization and graph cut optimization. Graph cut optimization is used twice, once to extract surface hypotheses from local Delaunay tetrahedralizations and once to merge overlapping surface hypotheses even when the local tetrahedralizations do not share the same topology.This formulation allows us to obtain a constant memory consumption per sub-problem while at the same time retaining the density independent interpolation properties of the Delaunay-based optimization. On multiple public datasets, we demonstrate that our approach is highly competitive with the state-of-the-art in terms of accuracy, completeness and outlier resilience. Further, we demonstrate the multi-scale potential of our approach by processing a newly recorded dataset with 2 billion points and a point density variation of more than four orders of magnitude - requiring less than 9GB of RAM per process.

##### Abstract (translated by Google)
在本文中，我们提出了一种可扩展的方法，用于从多尺度多视点立体点云中强大地计算三维表面网格，从而可以处理点密度的极端跳跃（在我们的实验中有三个数量级）。我们的方法的骨干是八叉树数据分割，局部Delaunay四面体化和图形切割优化的组合。图形切割优化被使用两次，一次从局部Delaunay四面体提取表面假设，一次合并重叠表面假设，即使当局部四面体化不共享相同的拓扑时。这个表达允许我们获得每个子问题的恒定内存消耗同时保持基于Delaunay优化的密度无关的插值性质。在多个公共数据集上，我们证明我们的方法在准确性，完整性和异常弹性方面与最先进的技术竞争非常激烈。此外，我们通过处理一个新记录的数据集，显示了我们方法的多尺度潜力，这个数据集有20亿个点，点密度变化超过四个数量级 - 每个过程需要少于9GB的RAM。

##### URL
[https://arxiv.org/abs/1705.00949](https://arxiv.org/abs/1705.00949)

##### PDF
[https://arxiv.org/pdf/1705.00949](https://arxiv.org/pdf/1705.00949)

