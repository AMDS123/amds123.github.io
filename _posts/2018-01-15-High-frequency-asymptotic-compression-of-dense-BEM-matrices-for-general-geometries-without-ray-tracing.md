---
layout: post
title: "High-frequency asymptotic compression of dense BEM matrices for general geometries without ray tracing"
date: 2018-01-15 15:11:04
categories: arXiv_SD
tags: arXiv_SD Sparse
author: Daan Huybrechs, Peter Opsomer
mathjax: true
---

* content
{:toc}

##### Abstract
Wave propagation and scattering problems in acoustics are often solved with boundary element methods. They lead to a discretization matrix that is typically dense and large: its size and condition number grow with increasing frequency. Yet, high frequency scattering problems are intrinsically local in nature, which is well represented by highly localized rays bouncing around. Asymptotic methods can be used to reduce the size of the linear system, even making it frequency independent, by explicitly extracting the oscillatory properties from the solution using ray tracing or analogous techniques. However, ray tracing becomes expensive or even intractable in the presence of (multiple) scattering obstacles with complicated geometries. In this paper, we start from the same discretization that constructs the fully resolved large and dense matrix, and achieve asymptotic compression by explicitly localizing the Green's function instead. This results in a large but sparse matrix, with a faster associated matrix-vector product and, as numerical experiments indicate, a much improved condition number. Though an appropriate localisation of the Green's function also depends on asymptotic information unavailable for general geometries, we can construct it adaptively in a frequency sweep from small to large frequencies in a way which automatically takes into account a general incident wave. We show that the approach is robust with respect to non-convex, multiple and even near-trapping domains, though the compression rate is clearly lower in the latter case. Furthermore, in spite of its asymptotic nature, the method is robust with respect to low-order discretizations such as piecewise constants, linears or cubics, commonly used in applications. On the other hand, we do not decrease the total number of degrees of freedom compared to a conventional classical discretization. The combination of the ...

##### Abstract (translated by Google)
声学中的波传播和散射问题通常用边界元方法解决。它们导致一个密度大且离散的矩阵：其大小和条件数量随着频率的增加而增长。然而，高频散射问题在本质上本质上是局部的，这是高度局部化的光线反射出来的。通过使用光线追踪或类似技术从解中明确提取振荡特性，可以使用渐近方法来减小线性系统的大小，甚至使其与频率无关。然而，在具有复杂几何形状的（多个）散射障碍存在的情况下，光线追踪变得昂贵或甚至难以处理。在本文中，我们从构造完全分解的大密度矩阵的相同离散开始，通过明确定位格林函数来实现渐近压缩。这导致了一个大而稀疏的矩阵，具有更快的关联矩阵向量乘积，并且如数值实验所指示的，条件数量大大改善。尽管格林函数的适当定位也依赖于一般几何不可用的渐近信息，但是我们可以自适应地将其构造成从小到大的频率以自动考虑一般入射波的方式扫频。我们证明这种方法在非凸，多个甚至接近囚禁域方面是稳健的，尽管在后一种情况下压缩率明显较低。此外，尽管其渐近性质，该方法对于在应用中通常使用的低阶离散（诸如分段常数，线性或立方体）是稳健的。另一方面，与传统的经典离散化相比，我们不减少自由度的总数。该组合的...

##### URL
[http://arxiv.org/abs/1606.09178](http://arxiv.org/abs/1606.09178)

##### PDF
[http://arxiv.org/pdf/1606.09178](http://arxiv.org/pdf/1606.09178)

