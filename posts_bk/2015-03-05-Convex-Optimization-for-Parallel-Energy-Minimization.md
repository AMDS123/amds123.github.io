---
layout: post
title: "Convex Optimization for Parallel Energy Minimization"
date: 2015-03-05 07:40:56
categories: arXiv_CV
tags: arXiv_CV Optimization
author: K. S. Sesh Kumar (LIENS,INRIA Paris - Rocquencourt), Alvaro Barbero, Stefanie Jegelka (MIT), Suvrit Sra (MIT), Francis Bach (LIENS,INRIA Paris - Rocquencourt)
mathjax: true
---

* content
{:toc}

##### Abstract
Energy minimization has been an intensely studied core problem in computer vision. With growing image sizes (2D and 3D), it is now highly desirable to run energy minimization algorithms in parallel. But many existing algorithms, in particular, some efficient combinatorial algorithms, are difficult to par-allelize. By exploiting results from convex and submodular theory, we reformulate the quadratic energy minimization problem as a total variation denoising problem, which, when viewed geometrically, enables the use of projection and reflection based convex methods. The resulting min-cut algorithm (and code) is conceptually very simple, and solves a sequence of TV denoising problems. We perform an extensive empirical evaluation comparing state-of-the-art combinatorial algorithms and convex optimization techniques. On small problems the iterative convex methods match the combinatorial max-flow algorithms, while on larger problems they offer other flexibility and important gains: (a) their memory footprint is small; (b) their straightforward parallelizability fits multi-core platforms; (c) they can easily be warm-started; and (d) they quickly reach approximately good solutions, thereby enabling faster "inexact" solutions. A key consequence of our approach based on submodularity and convexity is that it is allows to combine any arbitrary combinatorial or convex methods as subroutines, which allows one to obtain hybrid combinatorial and convex optimization algorithms that benefit from the strengths of both.

##### Abstract (translated by Google)
能量最小化一直是计算机视觉领域研究的核心问题。随着图像尺寸（2D和3D）的增长，现在非常希望并行运行能量最小化算法。但是许多现有的算法，特别是一些有效的组合算法，很难被并行化。通过利用凸和子模型理论的结果，我们将二次能量最小化问题作为一个总变差去噪问题进行了重新设计，当从几何角度观察时，能够使用基于投影和反射的凸方法。由此产生的最小切割算法（和代码）在概念上是非常简单的，并且解决了一系列电视去噪问题。我们进行了一个广泛的实证评估比较最先进的组合算法和凸优化技术。对于小问题，迭代凸方法匹配组合最大流算法，而在较大的问题上，它们提供了其他灵活性和重要收益：（a）它们的存储器占用面积小; （b）它们的直接并行性适合于多核平台; （c）可以很容易地开始热启动;和（四）他们很快达成大致的解决方案，从而使更快的“不精确的”解决方案。我们基于子模块性和凸性的方法的一个关键结果是允许将任意组合或凸的方法组合成子程序，从而允许获得混合的组合和凸的优化算法，这两个优化算法都受益于两者的优点。

##### URL
[https://arxiv.org/abs/1503.01563](https://arxiv.org/abs/1503.01563)

##### PDF
[https://arxiv.org/pdf/1503.01563](https://arxiv.org/pdf/1503.01563)

