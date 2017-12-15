---
layout: post
title: "Joint M-Best-Diverse Labelings as a Parametric Submodular Minimization"
date: 2016-06-23 08:10:46
categories: arXiv_CV
tags: arXiv_CV Optimization Relation
author: Alexander Kirillov, Alexander Shekhovtsov, Carsten Rother, Bogdan Savchynskyy
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of jointly inferring the M-best diverse labelings for a binary (high-order) submodular energy of a graphical model. Recently, it was shown that this problem can be solved to a global optimum, for many practically interesting diversity measures. It was noted that the labelings are, so-called, nested. This nestedness property also holds for labelings of a class of parametric submodular minimization problems, where different values of the global parameter $\gamma$ give rise to different solutions. The popular example of the parametric submodular minimization is the monotonic parametric max-flow problem, which is also widely used for computing multiple labelings. As the main contribution of this work we establish a close relationship between diversity with submodular energies and the parametric submodular minimization. In particular, the joint M-best diverse labelings can be obtained by running a non-parametric submodular minimization (in the special case - max-flow) solver for M different values of $\gamma$ in parallel, for certain diversity measures. Importantly, the values for $\gamma$ can be computed in a closed form in advance, prior to any optimization. These theoretical results suggest two simple yet efficient algorithms for the joint M-best diverse problem, which outperform competitors in terms of runtime and quality of results. In particular, as we show in the paper, the new methods compute the exact M-best diverse labelings faster than a popular method of Batra et al., which in some sense only obtains approximate solutions.

##### Abstract (translated by Google)
我们考虑共同推断图形模型的二元（高阶）子模块能量最好的多样标号的问题。最近，已经表明，这个问题可以被解决到全球最佳，许多实际上有趣的多样性措施。有人指出，标签是所谓的嵌套。这种嵌套属性也适用于一类参数子模块最小化问题的标签，其中全局参数$ \ gamma $的不同值引起不同的解决方案。参数子模最小化的流行例子是单调参数最大流问题，也被广泛用于计算多个标号。作为这项工作的主要贡献，我们建立了与子能量的多样性和参数子模极小化之间的密切关系。特别地，对于某些多样性度量，可以通过针对M个不同的$ \ gamma $值并行运行非参数子模块最小化（在特殊情况下 - 最大流量）求解器来获得联合M-最佳多样标签。重要的是，在任何优化之前，$ \ gamma $的值可以预先以封闭的形式计算。这些理论结果表明两种简单而有效的联合M-最佳多样性问题算法，在运行时间和结果质量方面优于竞争对手。具体而言，正如我们在文章中所展示的那样，新方法比Batra等人的流行方法更快地计算确切的M-最佳多样性标签，这在某种意义上只能获得近似解。

##### URL
[https://arxiv.org/abs/1606.07015](https://arxiv.org/abs/1606.07015)

##### PDF
[https://arxiv.org/pdf/1606.07015](https://arxiv.org/pdf/1606.07015)

