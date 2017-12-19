---
layout: post
title: "Direct Variational Perspective Shape from Shading with Cartesian Depth Parametrisation"
date: 2015-07-13 11:03:25
categories: arXiv_CV
tags: arXiv_CV Face
author: Yong Chul Ju, Daniel Maurer, Michael Breuß, Andrés Bruhn
mathjax: true
---

* content
{:toc}

##### Abstract
Most of today's state-of-the-art methods for perspective shape from shading are modelled in terms of partial differential equations (PDEs) of Hamilton-Jacobi type. To improve the robustness of such methods w.r.t. noise and missing data, first approaches have recently been proposed that seek to embed the underlying PDE into a variational framework with data and smoothness term. So far, however, such methods either make use of a radial depth parametrisation that makes the regularisation hard to interpret from a geometrical viewpoint or they consider indirect smoothness terms that require additional consistency constraints to provide valid solutions. Moreover the minimisation of such frameworks is an intricate task, since the underlying energy is typically non-convex. In our paper we address all three of the aforementioned issues. First, we propose a novel variational model that operates directly on the Cartesian depth. In this context, we also point out a common mistake in the derivation of the surface normal. Moreover, we employ a direct second-order regulariser with edge-preservation property. This direct regulariser yields by construction valid solutions without requiring additional consistency constraints. Finally, we also propose a novel coarse-to-fine minimisation framework based on an alternating explicit scheme. This framework allows us to avoid local minima during the minimisation and thus to improve the accuracy of the reconstruction. Experiments show the good quality of our model as well as the usefulness of the proposed numerical scheme.

##### Abstract (translated by Google)
大多数当前最先进的从阴影透视形状的方法都是用Hamilton-Jacobi类型的偏微分方程（PDE）来建模的。为了提高这种方法的稳健性，w.r.t.噪声和缺失数据，最近提出了第一种方法，试图将底层PDE嵌入到具有数据和平滑项的变化框架中。然而到目前为止，这种方法要么使用径向深度参数化，使得正则化难以从几何观点来解释，要么他们考虑间接平滑项，这需要额外的一致性约束来提供有效的解决方案。此外，这种框架的最小化是复杂的任务，因为基本的能量通常是非凸的。在我们的论文中，我们解决了上述三个问题。首先，我们提出了一个直接在笛卡儿深度上运行的新型变分模型。在这种情况下，我们也指出了表面法线推导中的一个常见错误。此外，我们使用一个具有边缘保存属性的直接二阶规则。这种直接的正规化者通过构建有效的解决方案而不需要额外的一致性约束。最后，我们还提出了一个基于交替显式方案的新颖的从粗到细的最小化框架。这个框架允许我们在最小化期间​​避免局部最小值，从而提高重建的准确性。实验表明，我们的模型的质量好，以及提出的数值方案的有用性。

##### URL
[https://arxiv.org/abs/1505.06163](https://arxiv.org/abs/1505.06163)

##### PDF
[https://arxiv.org/pdf/1505.06163](https://arxiv.org/pdf/1505.06163)

