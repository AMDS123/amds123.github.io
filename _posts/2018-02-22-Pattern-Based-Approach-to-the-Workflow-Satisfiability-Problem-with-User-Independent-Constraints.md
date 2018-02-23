---
layout: post
title: "Pattern-Based Approach to the Workflow Satisfiability Problem with User-Independent Constraints"
date: 2018-02-22 16:13:37
categories: arXiv_AI
tags: arXiv_AI
author: Daniel Karapetyan, Andrew J. Parkes, Gregory Gutin, Andrei Gagarin
mathjax: true
---

* content
{:toc}

##### Abstract
The fixed parameter tractable (FPT) approach is a powerful tool in tackling computationally hard problems. In this paper, we link FPT results to classic artificial intelligence (AI) techniques to show how they complement each other. Specifically, we consider the workflow satisfiability problem (WSP) which asks whether there exists an assignment of authorised users to the steps in a workflow specification, subject to certain constraints on the assignment. It was shown by Cohen et al. (JAIR 2014) that WSP restricted to the class of user-independent constraints (UI), covering many practical cases, admits FPT algorithms, i.e. can be solved in time exponential only in the number of steps $k$ and polynomial in the number of users $n$. Since usually $k \ll n$ in WSP, such FPT algorithms are of great practical interest as they significantly extend the size of the problem that can be routinely solved. 
 We give a new view of the FPT nature of the WSP with UI constraints, showing that it decomposes the problem into two levels. Exploiting this two-level split, we develop a new FPT algorithm that is by many orders of magnitude faster than the previous state-of-the-art WSP algorithm; and it also has only polynomial space complexity whereas the old algorithm takes memory exponential in $k$, which limits its application. 
 We also provide a new pseudo-boolean (PB) formulation of the WSP with UI constraints which exploits this new decomposition of the problem into two levels. Our experiments show that efficiency of solving this new PB formulation of the problem by a general purpose PB solver can be close to the bespoke FPT algorithm, which raises the potential of using general purpose solvers to tackle FPT problems efficiently. 
 We also study the computational performance of various algorithms to complement the overly-pessimistic worst-case analysis that is usually done in FPT studies.

##### Abstract (translated by Google)
固定参数易处理（FPT）方法是解决计算困难问题的有力工具。在本文中，我们将FPT结果与经典的人工智能（AI）技术相结合，以展示它们如何相互补充。具体而言，我们考虑工作流可满足性问题（WSP），该问题询问是否存在授权用户对工作流规范中的步骤的分配，但受分配的某些约束。 Cohen等人证明了这一点。 （JAIR 2014）认为WSP限于与用户无关的约束（UI）类别，涵盖许多实际情况，承认FPT算法，即可以按时间指数求解，仅在步骤数目k $和多项式数目用户$ n $。由于在WSP中通常是$ k \ ll n $，所以这些FPT算法具有很大的实际意义，因为它们显着扩大了可以常规解决的问题的大小。
 我们用UI约束给出了WSP的FPT性质的新视图，表明它将问题分解为两个层次。利用这种两级分割，我们开发了一种新的FPT算法，其速度比先前的最先进的WSP算法快许多数量级;并且它也只有多项式空间复杂度，而旧算法则以$ k $的内存指数函数，这限制了它的应用。
 我们还提供了一个新的带有UI约束的WSP的伪布尔（PB）公式，它将这个新的问题分解为两个层次。我们的实验表明，用通用PB解算器解决问题的新PB方案的效率可以接近定制的FPT算法，这提高了使用通用解算器有效解决FPT问题的潜力。
 我们还研究各种算法的计算性能，以补充通常在FPT研究中完成的过度悲观的最坏情况分析。

##### URL
[http://arxiv.org/abs/1604.05636](http://arxiv.org/abs/1604.05636)

##### PDF
[http://arxiv.org/pdf/1604.05636](http://arxiv.org/pdf/1604.05636)

