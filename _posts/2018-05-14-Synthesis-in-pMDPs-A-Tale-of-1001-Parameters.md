---
layout: post
title: "Synthesis in pMDPs: A Tale of 1001 Parameters"
date: 2018-05-14 19:58:54
categories: arXiv_AI
tags: arXiv_AI
author: Murat Cubuktepe, Nils Jansen, Sebastian Junges, Joost-Pieter Katoen, Ufuk Topcu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper considers parametric Markov decision processes (pMDPs) whose transitions are equipped with affine functions over a finite set of parameters. The synthesis problem is to find a parameter valuation such that the instantiated pMDP satisfies a specification under all strategies. We show that this problem can be formulated as a quadratically-constrained quadratic program (QCQP) and is non-convex in general. To deal with the NP-hardness of such problems, we exploit a convex-concave procedure (CCP) to iteratively obtain local optima. An appropriate interplay between CCP solvers and probabilistic model checkers creates a procedure --- realized in the open-source tool PROPhESY --- that solves the synthesis problem for models with thousands of parameters.

##### Abstract (translated by Google)
本文考虑参数马尔可夫决策过程（pMDPs），其过渡在有限的一组参数上配备仿射函数。综合问题是找到一个参数估值，使得实例化的pMDP满足所有策略下的规范。我们证明这个问题可以被定义为一个二次约束的二次规划（QCQP），并且通常是非凸的。为了处理这些问题的NP-硬度，我们利用凸凹过程（CCP）迭代地获得局部最优值。 CCP求解器和概率模型检查器之间的适当相互作用创建了一个程序---在开源工具PROPHESY中实现---解决了具有数千个参数的模型的综合问题。

##### URL
[http://arxiv.org/abs/1803.02884](http://arxiv.org/abs/1803.02884)

##### PDF
[http://arxiv.org/pdf/1803.02884](http://arxiv.org/pdf/1803.02884)

