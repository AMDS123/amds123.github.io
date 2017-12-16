---
layout: post
title: "LAP: a Linearize and Project Method for Solving Inverse Problems with Coupled Variables"
date: 2017-05-28 21:11:53
categories: arXiv_CV
tags: arXiv_CV Regularization Super_Resolution Optimization
author: James Herring, James Nagy, Lars Ruthotto
mathjax: true
---

* content
{:toc}

##### Abstract
Many inverse problems involve two or more sets of variables that represent different physical quantities but are tightly coupled with each other. For example, image super-resolution requires joint estimation of image and motion parameters from noisy measurements. Exploiting this structure is key for efficiently solving large-scale problems to avoid, e.g., ill-conditioned optimization problems. In this paper, we present a new method called Linearize And Project (LAP) that offers a flexible framework for solving inverse problems with coupled variables. LAP is most promising for cases when the subproblem corresponding to one of the variables is considerably easier to solve than the other. LAP is based on a Gauss-Newton method, and thus after linearizing the residual, it eliminates one block of variables through projection. Due to the linearization, the block can be chosen freely and can represent quadratic as well as nonlinear variables. Further, LAP supports direct, iterative, and hybrid regularization as well as constraints. Therefore LAP is attractive, e.g., for ill-posed imaging problems. These traits differentiate LAP from common alternatives for this type of problems such as variable projection (VarPro) and block coordinate descent (BCD). Our numerical experiments compare the performance of LAP to BCD and VarPro using four coupled problems with one quadratic and one nonlinear set of variables.

##### Abstract (translated by Google)
许多逆向问题涉及两组或多组代表不同物理量的变量，但彼此紧密耦合。例如，图像超分辨率需要来自噪声测量的图像和运动参数的联合估计。利用这种结构是有效地解决大规模问题以避免例如病态优化问题的关键。在本文中，我们提出了一个名为线性化和项目（LAP）的新方法，为解决耦合变量的反问题提供了一个灵活的框架。当相应于其中一个变量的子问题比其他变量更容易解决时，LAP最有希望。 LAP基于高斯 - 牛顿法，因此在对残差线性化之后，通过投影消除一个变量块。由于线性化，块可以自由选择，可以表示二次和非线性变量。此外，LAP支持直接，迭代和混合正则化以及约束。因此，LAP具有吸引力，例如，对于姿势不良的成像问题。这些特征将LAP与常见的替代方法区分开来，如可变投影（VarPro）和块坐标下降（BCD）等。我们的数值实验将LAP的性能与BCD和VarPro的性能进行比较，使用四个耦合问题，一个二次变量和一个非线性变量集合。

##### URL
[https://arxiv.org/abs/1705.09992](https://arxiv.org/abs/1705.09992)

##### PDF
[https://arxiv.org/pdf/1705.09992](https://arxiv.org/pdf/1705.09992)

