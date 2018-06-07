---
layout: post
title: "Constrained Counting and Sampling: Bridging the Gap between Theory and Practice"
date: 2018-06-06 15:16:32
categories: arXiv_AI
tags: arXiv_AI
author: Kuldeep S. Meel
mathjax: true
---

* content
{:toc}

##### Abstract
Constrained counting and sampling are two fundamental problems in Computer Science with numerous applications, including network reliability, privacy, probabilistic reasoning, and constrained-random verification. In constrained counting, the task is to compute the total weight, subject to a given weighting function, of the set of solutions of the given constraints. In constrained sampling, the task is to sample randomly, subject to a given weighting function, from the set of solutions to a set of given constraints. Consequently, constrained counting and sampling have been subject to intense theoretical and empirical investigations over the years. Prior work, however, offered either heuristic techniques with poor guarantees of accuracy or approaches with proven guarantees but poor performance in practice. 
 In this thesis, we introduce a novel hashing-based algorithmic framework for constrained sampling and counting that combines the classical algorithmic technique of universal hashing with the dramatic progress made in combinatorial reasoning tools, in particular, SAT and SMT, over the past two decades. The resulting frameworks for counting (ApproxMC2) and sampling (UniGen) can handle formulas with up to million variables representing a significant boost up from the prior state of the art tools' capability to handle few hundreds of variables. If the initial set of constraints is expressed as Disjunctive Normal Form (DNF), ApproxMC is the only known Fully Polynomial Randomized Approximation Scheme (FPRAS) that does not involve Monte Carlo steps. By exploiting the connection between definability of formulas and variance of the distribution of solutions in a cell defined by 3-universal hash functions, we introduced an algorithmic technique, MIS, that reduced the size of XOR constraints employed in the underlying universal hash functions by as much as two orders of magnitude.

##### Abstract (translated by Google)
约束计数和抽样是计算机科学中的两个基本问题，包括网络可靠性，隐私，概率推理和受限随机验证等众多应用。在约束计数中，任务是根据给定的加权函数计算给定约束的解集合的总权重。在约束采样中，任务是根据给定的加权函数随机抽样，从解集到一组给定约束。因此，多年来受限制的计数和采样一直受到强烈的理论和实证研究。但是，之前的工作提供了启发式技术，对准确性的保证很差，或者提供了经过验证的保证，但在实践中表现不佳。
 在这篇论文中，我们介绍了一种新颖的基于哈希的算法框架，用于约束采样和计数，它结合了通用哈希的经典算法技术和组合推理工具，特别是SAT和SMT在过去二十年取得的巨大进步。由此产生的计数框架（ApproxMC2）和采样（UniGen）可以处理多达一百万个变量的公式，这些变量代表了从先前技术工具处理数百个变量的能力的显着提升。如果最初的一组约束被表示为析取范式（DNF），则ApproxMC是唯一已知的完全多项式随机逼近方案（FPRAS），其不涉及蒙特卡罗步骤。通过利用公式的可定义性和由三通用散列函数定义的单元中解决方案分布的方差之间的联系，我们引入了一种算法技术MIS，其将基础通用散列函数中采用的XOR约束的大小减小为多达两个数量级。

##### URL
[http://arxiv.org/abs/1806.02239](http://arxiv.org/abs/1806.02239)

##### PDF
[http://arxiv.org/pdf/1806.02239](http://arxiv.org/pdf/1806.02239)

