---
layout: post
title: "LeapsAndBounds: A Method for Approximately Optimal Algorithm Configuration"
date: 2018-07-02 15:44:36
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Gell&#xe9;rt Weisz, Andr&#xe1;s Gy&#xf6;rgy, Csaba Szepesv&#xe1;ri
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of configuring general-purpose solvers to run efficiently on problem instances drawn from an unknown distribution. The goal of the configurator is to find a configuration that runs fast on average on most instances, and do so with the least amount of total work. It can run a chosen solver on a random instance until the solver finishes or a timeout is reached. We propose LeapsAndBounds, an algorithm that tests configurations on randomly selected problem instances for longer and longer time. We prove that the capped expected runtime of the configuration returned by LeapsAndBounds is close to the optimal expected runtime, while our algorithm's running time is near-optimal. Our results show that LeapsAndBounds is more efficient than the recent algorithm of Kleinberg et al. (2017), which, to our knowledge, is the only other algorithm configuration method with non-trivial theoretical guarantees. Experimental results on configuring a public SAT solver on a new benchmark dataset also stand witness to the superiority of our method.

##### Abstract (translated by Google)
我们考虑配置通用解算器以在从未知分布中提取的问题实例上有效运行的问题。配置程序的目标是找到在大多数实例上平均运行速度快的配置，并以最少的总工作量执行此操作。它可以在随机实例上运行选定的求解器，直到求解器完成或达到超时。我们提出LeapsAndBounds，这是一种在随机选择的问题实例上测试配置的时间越来越长的算法。我们证明LeapsAndBounds返回的配置的上限预期运行时间接近最佳预期运行时间，而我们算法的运行时间接近最优。我们的结果表明LeapsAndBounds比最近的Kleinberg等算法更有效。 （2017），据我们所知，这是唯一一种具有非平凡理论保证的算法配置方法。在新的基准数据集上配置公共SAT求解器的实验结果也证明了我们方法的优越性。

##### URL
[http://arxiv.org/abs/1807.00755](http://arxiv.org/abs/1807.00755)

##### PDF
[http://arxiv.org/pdf/1807.00755](http://arxiv.org/pdf/1807.00755)

