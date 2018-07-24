---
layout: post
title: "Scalable Tensor Completion with Nonconvex Regularization"
date: 2018-07-23 17:12:01
categories: arXiv_AI
tags: arXiv_AI Regularization Optimization
author: Quanming Yao
mathjax: true
---

* content
{:toc}

##### Abstract
Low-rank tensor completion problem aims to recover a tensor from limited observations, which has many real-world applications. Due to the easy optimization, the convex overlapping nuclear norm has been popularly used for tensor completion. However, it over-penalizes top singular values and lead to biased estimations. In this paper, we propose to use the nonconvex regularizer, which can less penalize large singular values, instead of the convex one for tensor completion. However, as the new regularizer is nonconvex and overlapped with each other, existing algorithms are either too slow or suffer from the huge memory cost. To address these issues, we develop an efficient and scalable algorithm, which is based on the proximal average (PA) algorithm, for real-world problems. Compared with the direct usage of PA algorithm, the proposed algorithm runs orders faster and needs orders less space. We further speed up the proposed algorithm with the acceleration technique, and show the convergence to critical points is still guaranteed. Experimental comparisons of the proposed approach are made with various other tensor completion approaches. Empirical results show that the proposed algorithm is very fast and can produce much better recovery performance.

##### Abstract (translated by Google)
低秩张量完成问题旨在从有限的观测中恢复张量，该观测具有许多实际应用。由于易于优化，凸重叠核范数已普遍用于张量完成。然而，它过分惩罚顶级奇异值并导致有偏差的估计。在本文中，我们建议使用非凸正则化器，它可以较少惩罚大的奇异值，而不是凸起的张量完成。然而，由于新的正则化器是非凸的并且彼此重叠，现有的算法要么太慢，要么遭受巨大的存储器成本。为了解决这些问题，我们开发了一种高效且可扩展的算法，该算法基于近端平均（PA）算法，用于解决实际问题。与直接使用PA算法相比，该算法可以更快地运行命令，并且需要更少的空间。我们利用加速技术进一步加快了算法的速度，并且仍然保证了对临界点的收敛性。使用各种其他张量完成方法对所提出的方法进行实验比较。实证结果表明，该算法速度快，可以产生更好的恢复性能。

##### URL
[http://arxiv.org/abs/1807.08725](http://arxiv.org/abs/1807.08725)

##### PDF
[http://arxiv.org/pdf/1807.08725](http://arxiv.org/pdf/1807.08725)

