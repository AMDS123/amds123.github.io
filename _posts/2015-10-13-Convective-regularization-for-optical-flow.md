---
layout: post
title: "Convective regularization for optical flow"
date: 2015-10-13 11:24:36
categories: arXiv_CV
tags: arXiv_CV Regularization
author: José A. Iglesias, Clemens Kirisits
mathjax: true
---

* content
{:toc}

##### Abstract
We argue that the time derivative in a fixed coordinate frame may not be the most appropriate measure of time regularity of an optical flow field. Instead, for a given velocity field $v$ we consider the convective acceleration $v_t + \nabla v v$ which describes the acceleration of objects moving according to $v$. Consequently we investigate the suitability of the nonconvex functional $\|v_t + \nabla v v\|^2_{L^2}$ as a regularization term for optical flow. We demonstrate that this term acts as both a spatial and a temporal regularizer and has an intrinsic edge-preserving property. We incorporate it into a contrast invariant and time-regularized variant of the Horn-Schunck functional, prove existence of minimizers and verify experimentally that it addresses some of the problems of basic quadratic models. For the minimization we use an iterative scheme that approximates the original nonlinear problem with a sequence of linear ones. We believe that the convective acceleration may be gainfully introduced in a variety of optical flow models.

##### Abstract (translated by Google)
我们认为固定坐标系下的时间导数可能不是光流场时间规律的最合适的量度。相反，对于给定的速度场$ v $，我们考虑对流加速度$ v_t + \ nabla v v $，它描述了物体按$ v $移动的加速度。因此，我们研究了非凸函数$ \ | v_t + \ nabla \ v \ \ ^ 2_ {L ^ 2} $作为光流正则化项的适用性。我们证明这个术语充当了空间和时间正规化器，并且具有内在的边缘保留特性。我们将其纳入Horn-Schunck函数的对比不变和时间规则变体，证明极小值的存在性，并通过实验验证它解决了基本二次模型的一些问题。为了最小化，我们使用一个迭代方案，用一系列线性方程逼近原始的非线性问题。我们相信，对流加速度可能会在各种光流模型中有效地引入。

##### URL
[https://arxiv.org/abs/1505.04938](https://arxiv.org/abs/1505.04938)

##### PDF
[https://arxiv.org/pdf/1505.04938](https://arxiv.org/pdf/1505.04938)

