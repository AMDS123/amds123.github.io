---
layout: post
title: "Sparse Approximation of 3D Meshes using the Spectral Geometry of the Hamiltonian Operator"
date: 2018-05-12 20:20:59
categories: arXiv_CV
tags: arXiv_CV Sparse Face
author: Yoni Choukroun, Gautam Pai, Ron Kimmel
mathjax: true
---

* content
{:toc}

##### Abstract
The discrete Laplace operator is ubiquitous in spectral shape analysis, since its eigenfunctions are provably optimal in representing smooth functions defined on the surface of the shape. Indeed, subspaces defined by its eigenfunctions have been utilized for shape compression, treating the coordinates as smooth functions defined on the given surface. However, surfaces of shapes in nature often contain geometric structures for which the general smoothness assumption may fail to hold. At the other end, some explicit mesh compression algorithms utilize the order by which vertices that represent the surface are traversed, a property which has been ignored in spectral approaches. Here, we incorporate the order of vertices into an operator that defines a novel spectral domain. We propose a method for representing 3D meshes using the spectral geometry of the Hamiltonian operator, integrated within a sparse approximation framework. We adapt the concept of a potential function from quantum physics and incorporate vertex ordering information into the potential, yielding a novel data-dependent operator. The potential function modifies the spectral geometry of the Laplacian to focus on regions with finer details of the given surface. By sparsely encoding the geometry of the shape using the proposed data-dependent basis, we improve compression performance compared to previous results that use the standard Laplacian basis and spectral graph wavelets.

##### Abstract (translated by Google)
离散拉普拉斯算子在频谱形状分析中无处不在，因为它的本征函数在表示在形状表面上定义的平滑函数时可证明是最佳的。事实上，由其本征函数定义的子空间已被用于形状压缩，将坐标视为给定表面上定义的光滑函数。然而，自然界中的形状表面通常包含几何结构，一般的平滑假设可能无法保持。另一方面，一些明确的网格压缩算法利用表示表面的顶点的遍历顺序，这是一种在频谱方法中被忽略的性质。在这里，我们将顶点的顺序合并到定义一个新的频谱域的算子中。我们提出了一种用哈密尔顿算子的谱几何表示三维网格的方法，它集成在稀疏近似框架内。我们调整了量子物理中的潜在函数的概念，并将顶点排序信息纳入潜力，产生了一种新型的数据相关算子。势函数修改了拉普拉斯算子的谱几何关注点，使其聚焦在给定曲面的更精细的区域上。通过使用所提出的数据相关基础对形状的几何进行稀疏编码，与使用标准拉普拉斯基和谱图小波的先前结果相比，我们改进了压缩性能。

##### URL
[http://arxiv.org/abs/1707.02120](http://arxiv.org/abs/1707.02120)

##### PDF
[http://arxiv.org/pdf/1707.02120](http://arxiv.org/pdf/1707.02120)

