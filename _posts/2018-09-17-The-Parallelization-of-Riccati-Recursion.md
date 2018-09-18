---
layout: post
title: "The Parallelization of Riccati Recursion"
date: 2018-09-17 17:54:23
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Forrest Laine, Claire Tomlin
mathjax: true
---

* content
{:toc}

##### Abstract
A method is presented for parallelizing the computation of solutions to discrete-time, linear-quadratic, finite-horizon optimal control problems, which we will refer to as LQR problems. This class of problem arises frequently in robotic trajectory optimization. For very complicated robots, the size of these resulting problems can be large enough that computing the solution is prohibitively slow when using a single processor. Fortunately, approaches to solving these type of problems based on numerical solutions to the KKT conditions of optimality offer a parallel solution method and can leverage multiple processors to compute solutions faster. However, these methods do not produce the useful feedback control policies that are generated as a by-product of the dynamic-programming solution method known as Riccati recursion. In this paper we derive a method which is able to parallelize the computation of Riccati recursion, allowing for super-fast solutions to the LQR problem while still generating feedback control policies. We demonstrate empirically that our method is faster than existing parallel methods.

##### Abstract (translated by Google)
提出了一种方法，用于将解决方案的计算并行化为离散时间，线性二次，有限时域最优控制问题，我们将其称为LQR问题。这类问题经常出现在机器人轨迹优化中。对于非常复杂的机器人，这些问题的大小可能足够大，以至于在使用单个处理器时计算解决方案的速度非常慢。幸运的是，基于KKT最优性条件的数值解决方案来解决这些类型问题的方法提供了并行解决方案，并且可以利用多个处理器更快地计算解决方案。但是，这些方法不会产生有用的反馈控制策略，这些策略是作为称为Riccati递归的动态编程解决方法的副产品生成的。在本文中，我们推导出一种能够并行化Riccati递归计算的方法，允许在仍然生成反馈控制策略的同时实现LQR问题的超快解。我们凭经验证明我们的方法比现有的并行方法更快。

##### URL
[http://arxiv.org/abs/1809.06360](http://arxiv.org/abs/1809.06360)

##### PDF
[http://arxiv.org/pdf/1809.06360](http://arxiv.org/pdf/1809.06360)

