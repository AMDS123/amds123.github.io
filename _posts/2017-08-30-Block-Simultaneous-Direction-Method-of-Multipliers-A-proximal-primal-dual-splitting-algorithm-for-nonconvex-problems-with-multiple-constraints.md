---
layout: post
title: "Block-Simultaneous Direction Method of Multipliers: A proximal primal-dual splitting algorithm for nonconvex problems with multiple constraints"
date: 2017-08-30 00:15:50
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Fred Moolekamp, Peter Melchior
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a generalization of the linearized Alternating Direction Method of Multipliers to optimize a real-valued function $f$ of multiple arguments with potentially multiple constraints $g_\circ$ on each of them. The function $f$ may be nonconvex as long as it is convex in every argument, while the constraints $g_\circ$ need to be convex but not smooth. If $f$ is smooth, the proposed Block-Simultaneous Direction Method of Multipliers (bSDMM) can be interpreted as a proximal analog to inexact coordinate descent methods under constraints. Unlike alternative approaches for joint solvers of multiple-constraint problems, we do not require linear operators $L$ of a constraint function $g(L\ \cdot)$ to be invertible or linked between each other. bSDMM is well-suited for a range of optimization problems, in particular for data analysis, where $f$ is the likelihood function of a model and $L$ could be a transformation matrix describing e.g. finite differences or basis transforms. We apply bSDMM to the Non-negative Matrix Factorization task of a hyperspectral unmixing problem and demonstrate convergence and effectiveness of multiple constraints on both matrix factors. The algorithms are implemented in python and released as an open-source package.

##### Abstract (translated by Google)
我们引入线性交替方向乘法器的推广，以优化具有潜在的多个约束$ g_ \ circ $的多个参数的实值函数$ f $。只要函数$ f $在每个参数中都是凸的，函数$ f $也可以是非凸的，而$ g_ \ circ $需要是凸的而不是平滑的。如果$ f $是平滑的，则所提出的块 - 同时方向乘法器（bSDMM）可以被解释为在约束下的不精确坐标下降方法的近似模拟。与多约束问题的联合求解器的替代方法不同，我们并不要求约束函数$ g（L \ \ cdot）$的线性算子$ L $是可逆或相互之间的链接。 bSDMM非常适用于一系列优化问题，特别是对于数据分析，其中$ f $是模型的似然函数，$ L $可以是一个变换矩阵，用于描述例如有限差异或基础变换。我们将bSDMM应用于高光谱分解问题的非负矩阵分解任务，并证明了两个矩阵因子的多重约束的收敛性和有效性。这些算法在Python中实现，并作为开源软件包发布。

##### URL
[https://arxiv.org/abs/1708.09066](https://arxiv.org/abs/1708.09066)

##### PDF
[https://arxiv.org/pdf/1708.09066](https://arxiv.org/pdf/1708.09066)

