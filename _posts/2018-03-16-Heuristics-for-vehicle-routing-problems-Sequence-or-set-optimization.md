---
layout: post
title: "Heuristics for vehicle routing problems: Sequence or set optimization?"
date: 2018-03-16 03:00:18
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Túlio A. M. Toffolo, Thibaut Vidal, Tony Wauters
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate a structural decomposition for the capacitated vehicle routing problem (CVRP) based on vehicle-to-customer "assignment" and visits "sequencing" decision variables. We show that an heuristic search focused on assignment decisions with a systematic optimal choice of sequences (using Concorde TSP solver) during each move evaluation is promising but requires a prohibitive computational effort. We therefore introduce an intermediate search space, based on the dynamic programming procedure of Balas & Simonetti, which finds a good compromise between intensification and computational efficiency. A variety of speed-up techniques are proposed for a fast exploration: neighborhood reductions, dynamic move filters, memory structures, and concatenation techniques. Finally, a tunneling strategy is designed to reshape the search space as the algorithm progresses. The combination of these techniques within a classical local search, as well as in the unified hybrid genetic search (UHGS) leads to significant improvements of solution accuracy. New best solutions are found for surprisingly small instances with as few as 256 customers. These solutions had not been attained up to now with classic neighborhoods. Overall, this research permits to better evaluate the respective impact of sequence and assignment optimization, proposes new ways of combining the optimization of these two decision sets, and opens promising research perspectives for the CVRP and its variants.

##### Abstract (translated by Google)
我们研究基于车辆到客户“分配”的访问“排序”决策变量的能力化车辆路径问题（CVRP）的结构分解。我们表明，在每次移动评估期间，使用系统性序列最优选择（使用Concorde TSP求解器）的集中在分配决策上的启发式搜索是有前途的，但是需要极高的计算量。因此，我们引入一个中间搜索空间，基于Balas＆Simonetti的动态编程过程，该过程在强化和计算效率之间找到了一个很好的折衷。为快速探索提出了各种加速技术：邻域减少，动态移动过滤器，内存结构和连接技术。最后，隧道策略被设计为随着算法的进展重塑搜索空间。这些技术在经典的局部搜索以及统一的混合遗传搜索（UHGS）中的结合导致解决方案准确性的显着提高。全新的最佳解决方案适用于只有256位客户的令人惊讶的小型实例。这些解决方案到现在还没有达到经典社区。总的来说，这项研究可以更好地评估序列和分配优化的各自影响，提出结合这两个决策集优化的新方法，并为CVRP及其变体打开有前景的研究观点。

##### URL
[https://arxiv.org/abs/1803.06062](https://arxiv.org/abs/1803.06062)

##### PDF
[https://arxiv.org/pdf/1803.06062](https://arxiv.org/pdf/1803.06062)

