---
layout: post
title: "An Octree-Based Approach towards Efficient Variational Range Data Fusion"
date: 2016-08-26 10:01:51
categories: arXiv_CV
tags: arXiv_CV Sparse Optimization
author: Wadim Kehl, Tobias Holl, Federico Tombari, Slobodan Ilic, Nassir Navab
mathjax: true
---

* content
{:toc}

##### Abstract
Volume-based reconstruction is usually expensive both in terms of memory consumption and runtime. Especially for sparse geometric structures, volumetric representations produce a huge computational overhead. We present an efficient way to fuse range data via a variational Octree-based minimization approach by taking the actual range data geometry into account. We transform the data into Octree-based truncated signed distance fields and show how the optimization can be conducted on the newly created structures. The main challenge is to uphold speed and a low memory footprint without sacrificing the solutions' accuracy during optimization. We explain how to dynamically adjust the optimizer's geometric structure via joining/splitting of Octree nodes and how to define the operators. We evaluate on various datasets and outline the suitability in terms of performance and geometric accuracy.

##### Abstract (translated by Google)
在内存消耗和运行时间方面，基于卷的重建通常都很昂贵。特别是对于稀疏的几何结构，体积表示会产生巨大的计算开销。我们提出一种有效的方法来融合范围数据，通过考虑实际的距离数据几何结构，通过基于变分八叉树的最小化方法。我们将数据转换为基于八叉树的截断符号距离字段，并显示如何在新创建的结构上进行优化。主要挑战是在优化过程中不牺牲解决方案的准确性的情况下维持速度和低内存占用。我们解释如何通过连接/分割八叉树节点以及如何定义运算符来动态调整优化器的几何结构。我们评估各种数据集，并概述性能和几何精度方面的适用性。

##### URL
[https://arxiv.org/abs/1608.07411](https://arxiv.org/abs/1608.07411)

##### PDF
[https://arxiv.org/pdf/1608.07411](https://arxiv.org/pdf/1608.07411)

