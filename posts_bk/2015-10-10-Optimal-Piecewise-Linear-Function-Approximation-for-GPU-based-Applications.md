---
layout: post
title: "Optimal Piecewise Linear Function Approximation for GPU-based Applications"
date: 2015-10-10 20:49:17
categories: arXiv_CV
tags: arXiv_CV
author: Daniel Berjón, Guillermo Gallego, Carlos Cuevas, Francisco Morán, Narciso García
mathjax: true
---

* content
{:toc}

##### Abstract
Many computer vision and human-computer interaction applications developed in recent years need evaluating complex and continuous mathematical functions as an essential step toward proper operation. However, rigorous evaluation of this kind of functions often implies a very high computational cost, unacceptable in real-time applications. To alleviate this problem, functions are commonly approximated by simpler piecewise-polynomial representations. Following this idea, we propose a novel, efficient, and practical technique to evaluate complex and continuous functions using a nearly optimal design of two types of piecewise linear approximations in the case of a large budget of evaluation subintervals. To this end, we develop a thorough error analysis that yields asymptotically tight bounds to accurately quantify the approximation performance of both representations. It provides an improvement upon previous error estimates and allows the user to control the trade-off between the approximation error and the number of evaluation subintervals. To guarantee real-time operation, the method is suitable for, but not limited to, an efficient implementation in modern Graphics Processing Units (GPUs), where it outperforms previous alternative approaches by exploiting the fixed-function interpolation routines present in their texture units. The proposed technique is a perfect match for any application requiring the evaluation of continuous functions, we have measured in detail its quality and efficiency on several functions, and, in particular, the Gaussian function because it is extensively used in many areas of computer vision and cybernetics, and it is expensive to evaluate.

##### Abstract (translated by Google)
近年来发展起来的许多计算机视觉和人机交互应用程序需要评估复杂和连续的数学函数，作为实现正确操作的关键步骤。然而，对这种功能的严格评估通常意味着非常高的计算成本，在实时应用中是不可接受的。为了缓解这个问题，通常用更简单的分段多项式表示来近似函数。遵循这个想法，我们提出了一种新颖，高效和实用的技术来评估复杂和连续的功能，使用两种类型的分段线性逼近的近似最优设计，在预算较大的评估子区间的情况下。为此，我们开发了一个彻底的错误分析，产生渐近的严格界限，准确量化两个表示的近似性能。它提供了对先前误差估计的改进，并允许用户控制近似误差与评估子区间数量之间的折衷。为了保证实时操作，该方法适用于但不限于现代图形处理单元（GPU）中的有效实现，其中它通过利用存在于其纹理单元中的固定功能插值例程而优于先前的替代方法。所提出的技术是任何需要连续函数评估的应用的完美匹配，我们已经详细地测量了它在多个函数上的质量和效率，特别是高斯函数，因为它广泛地用于计算机视觉的许多领域，控制论，评估昂贵。

##### URL
[https://arxiv.org/abs/1510.02975](https://arxiv.org/abs/1510.02975)

##### PDF
[https://arxiv.org/pdf/1510.02975](https://arxiv.org/pdf/1510.02975)

