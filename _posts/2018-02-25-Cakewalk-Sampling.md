---
layout: post
title: "Cakewalk Sampling"
date: 2018-02-25 16:15:32
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Uri Patish, Shimon Ullman
mathjax: true
---

* content
{:toc}

##### Abstract
Combinatorial optimization is a common theme in computer science which underlies a considerable variety of problems. In contrast to the continuous setting, combinatorial problems require special solution strategies, and it's hard to come by generic schemes like gradient methods for continuous domains. We follow a standard construction of a parametric sampling distribution that transforms the problem to the continuous domain, allowing us to optimize the expectation of a given objective using estimates of the gradient. In spite of the apparent generality, such constructions are known to suffer from highly variable gradient estimates, and thus require careful tuning that is done in a problem specific manner. We show that a simple trick of converting the objective values to their cumulative probabilities fixes the distribution of the objective, allowing us to derive an online optimization algorithm that can be applied in a generic fashion. As an experimental benchmark we use the task of finding cliques in undirected graphs, and we show that our method, even when blindly applied, consistently outperforms related methods. Notably, on the DIMACS clique benchmark, our method approaches the performance of the best clique finding algorithms without access to the graph structure, and only through objective function evaluations, thus providing significant evidence to the generality and effectivity of our method.

##### Abstract (translated by Google)
组合优化是计算机科学中的一个常见主题，它是各种问题的基础。与连续设置相比，组合问题需要特殊的解决方案策略，很难通过像连续域的梯度方法这样的通用方案来实现。我们遵循一个参数抽样分布的标准构造，将问题转换为连续域，使我们能够使用梯度估计来优化给定目标的期望。尽管具有明显的一般性，但这样的构造已知会受到高度变化的梯度估计的影响，因此需要仔细调整，以特定问题的方式完成。我们表明，将目标值转换为其累积概率的简单技巧可以修正目标的分布，从而使我们能够推导出可以以通用方式应用的在线优化算法。作为一个实验性基准，我们使用在无向图中找到派系的任务，并且我们显示，即使在盲目应用时，我们的方法也始终优于相关方法。值得注意的是，在DIMACS集团基准测试中，我们的方法接近无法访问图结构的最佳集团查找算法的性能，并且仅通过目标函数评估，从而为我们的方法的一般性和有效性提供了重要证据。

##### URL
[http://arxiv.org/abs/1802.09030](http://arxiv.org/abs/1802.09030)

##### PDF
[http://arxiv.org/pdf/1802.09030](http://arxiv.org/pdf/1802.09030)

