---
layout: post
title: "Large Neighborhood-Based Metaheuristic and Branch-and-Price for the Pickup and Delivery Problem with Split Loads"
date: 2018-02-18 02:09:20
categories: arXiv_AI
tags: arXiv_AI
author: Matheus Nohra Haddad, Rafael Martinelli, Thibaut Vidal, Luiz Satoru Ochi, Simone Martins, Marcone Jamilson Freitas Souza, Richard Hartl
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the multi-vehicle one-to-one pickup and delivery problem with split loads, a NP-hard problem linked with a variety of applications for bulk product transportation, bike-sharing systems and inventory re-balancing. This problem is notoriously difficult due to the interaction of two challenging vehicle routing attributes, "pickups and deliveries" and "split deliveries". This possibly leads to optimal solutions of a size that grows exponentially with the instance size, containing multiple visits per customer pair, even in the same route. To solve this problem, we propose an iterated local search metaheuristic as well as a branch-and-price algorithm. The core of the metaheuristic consists of a new large neighborhood search, which reduces the problem of finding the best insertion combination of a pickup and delivery pair into a route (with possible splits) to a resource-constrained shortest path and knapsack problem. Similarly, the branch-and-price algorithm uses sophisticated labeling techniques, route relaxations, pre-processing and branching rules for an efficient resolution. Our computational experiments on classical single-vehicle instances demonstrate the excellent performance of the metaheuristic, which produces new best known solutions for 92 out of 93 test instances, and outperforms all previous algorithms. Experimental results on new multi-vehicle instances with distance constraints are also reported. The branch-and-price algorithm produces optimal solutions for instances with up to 20 pickup-and-delivery pairs, and very accurate solutions are found by the metaheuristic.

##### Abstract (translated by Google)
我们认为多车一对一的分拣装载和分拣装载的交付问题，与批量产品运输，自行车共享系统和库存重新平衡等各种应用相关的NP难题。由于两个具有挑战性的车辆路线属性，“拾取和交付”和“拆分交付”的相互作用，这个问题非常困难。这可能会导致尺寸与实例大小成指数增长的最佳解决方案，即使在相同的路线中也包含每个客户对的多次访问。为了解决这个问题，我们提出了一种迭代本地搜索的元启发式算法以及分支和价格算法。元启发式算法的核心是一个新的大型邻域搜索，它减少了将拾取和传递对组合成一个路径（可能发生分裂）到资源受限最短路径和背包问题的最佳插入组合问题。同样，分支和价格算法使用复杂的标签技术，路线松弛，预处理和分支规则以实现高效的解决方案。我们在经典的单车实例上进行的计算实验证明了元启发式的优秀性能，它为93个测试实例中的92个产生了新的最知名的解决方案，并且优于以前的所有算法。还报道了具有距离约束的新的多车辆实例的实验结果。分支和价格算法为具有多达20个拾取 - 递送对的实例产生最佳解决方案，并且通过元启发式找到非常准确的解决方案。

##### URL
[http://arxiv.org/abs/1802.06318](http://arxiv.org/abs/1802.06318)

##### PDF
[http://arxiv.org/pdf/1802.06318](http://arxiv.org/pdf/1802.06318)

