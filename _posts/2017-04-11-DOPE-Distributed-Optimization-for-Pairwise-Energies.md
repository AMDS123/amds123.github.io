---
layout: post
title: "DOPE: Distributed Optimization for Pairwise Energies"
date: 2017-04-11 02:21:13
categories: arXiv_CV
tags: arXiv_CV Segmentation Optimization
author: Jose Dolz, Ismail Ben Ayed, Christian Desrosiers
mathjax: true
---

* content
{:toc}

##### Abstract
We formulate an Alternating Direction Method of Mul-tipliers (ADMM) that systematically distributes the computations of any technique for optimizing pairwise functions, including non-submodular potentials. Such discrete functions are very useful in segmentation and a breadth of other vision problems. Our method decomposes the problem into a large set of small sub-problems, each involving a sub-region of the image domain, which can be solved in parallel. We achieve consistency between the sub-problems through a novel constraint that can be used for a large class of pair-wise functions. We give an iterative numerical solution that alternates between solving the sub-problems and updating consistency variables, until convergence. We report comprehensive experiments, which demonstrate the benefit of our general distributed solution in the case of the popular serial algorithm of Boykov and Kolmogorov (BK algorithm) and, also, in the context of non-submodular functions.

##### Abstract (translated by Google)
我们制定了一个交互方向的多阶段方法（ADMM），系统地分配任何技术的计算，以优化配对函数，包括非子模块电位。这些离散函数在分割和其他视觉问题的广度上是非常有用的。我们的方法将问题分解成一大组小的子问题，每个问题涉及图像域的子区域，可以并行求解。我们通过一个新的约束来实现子问题之间的一致性，这个约束可以用于大量的成对函数。我们给出了一个迭代的数值解决方案，在解决子问题和更新一致性变量之间交替，直到收敛。我们报告了全面的实验，这些实验证明了在Boykov和Kolmogorov（BK算法）流行的串行算法的情况下以及在非子模块函数的情况下我们的通用分布式解决方案的益处。

##### URL
[https://arxiv.org/abs/1704.03116](https://arxiv.org/abs/1704.03116)

##### PDF
[https://arxiv.org/pdf/1704.03116](https://arxiv.org/pdf/1704.03116)

