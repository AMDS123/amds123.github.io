---
layout: post
title: "$ell_p$-Box ADMM: A Versatile Framework for Integer Programming"
date: 2016-06-19 12:53:02
categories: arXiv_CV
tags: arXiv_CV
author: Baoyuan Wu, Bernard Ghanem
mathjax: true
---

* content
{:toc}

##### Abstract
This paper revisits the integer programming (IP) problem, which plays a fundamental role in many computer vision and machine learning applications. The literature abounds with many seminal works that address this problem, some focusing on continuous approaches (e.g. linear program relaxation) while others on discrete ones (e.g., min-cut). However, a limited number of them are designed to handle the general IP form and even these methods cannot adequately satisfy the simultaneous requirements of accuracy, feasibility, and scalability. To this end, we propose a novel and versatile framework called $\ell_p$-box ADMM, which is based on two parts. (1) The discrete constraint is equivalently replaced by the intersection of a box and a $(n-1)$-dimensional sphere (defined through the $\ell_p$ norm). (2) We infuse this equivalence into the ADMM (Alternating Direction Method of Multipliers) framework to handle these continuous constraints separately and to harness its attractive properties. More importantly, the ADMM update steps can lead to manageable sub-problems in the continuous domain. To demonstrate its efficacy, we consider an instance of the framework, namely $\ell_2$-box ADMM applied to binary quadratic programming (BQP). Here, the ADMM steps are simple, computationally efficient, and theoretically guaranteed to converge to a KKT point. We demonstrate the applicability of $\ell_2$-box ADMM on three important applications: MRF energy minimization, graph matching, and clustering. Results clearly show that it significantly outperforms existing generic IP solvers both in runtime and objective. It also achieves very competitive performance vs. state-of-the-art methods specific to these applications.

##### Abstract (translated by Google)
本文重新讨论了整数规划（IP）问题，它在许多计算机视觉和机器学习应用中起着重要的作用。文献中充斥着许多解决这个问题的开创性着作，其中一些着眼于连续的方法（例如线性程序放松）而另一些着重于离散的（例如最小切割）。然而，其中有限的一些是为处理一般的IP形式而设计的，甚至这些方法也不能充分满足准确性，可行性和可扩展性的同时要求。为此，我们提出了一个新颖而多样的框架，叫做$ \ ell_p $ -box ADMM，它基于两部分。 （1）离散约束等价地被一个盒子和一个$（n-1）$维球体（通过$ \ ell_p $ norm定义）的交点替换。 （2）我们将这种等价性注入到ADMM（交替方向乘法器）框架中，以分别处理这些连续的约​​束条件，并利用其吸引人的特性。更重要的是，ADMM更新步骤可能导致连续域中可管理的子问题。为证明其有效性，我们考虑一个框架实例，即应用于二进制二次规划（BQP）的$ \ ell_2 $ -box ADMM。这里，ADMM步骤简单，计算效率高，理论上保证收敛到KKT点。我们证明了$ \ ell_2 $ -box ADMM在三个重要应用上的适用性：MRF能量最小化，图匹配和聚类。结果清楚地表明，它在运行时和客观方面明显优于现有的通用IP解算器。与特定于这些应用的最先进的方法相比，它也实现了非常有竞争力的性能。

##### URL
[https://arxiv.org/abs/1604.07666](https://arxiv.org/abs/1604.07666)

##### PDF
[https://arxiv.org/pdf/1604.07666](https://arxiv.org/pdf/1604.07666)

