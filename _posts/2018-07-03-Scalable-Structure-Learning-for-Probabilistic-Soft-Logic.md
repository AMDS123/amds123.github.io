---
layout: post
title: "Scalable Structure Learning for Probabilistic Soft Logic"
date: 2018-07-03 04:25:23
categories: arXiv_AI
tags: arXiv_AI Optimization Relation
author: Varun Embar, Dhanya Sridhar, Golnoosh Farnadi, Lise Getoor
mathjax: true
---

* content
{:toc}

##### Abstract
Statistical relational frameworks such as Markov logic networks and probabilistic soft logic (PSL) encode model structure with weighted first-order logical clauses. Learning these clauses from data is referred to as structure learning. Structure learning alleviates the manual cost of specifying models. However, this benefit comes with high computational costs; structure learning typically requires an expensive search over the space of clauses which involves repeated optimization of clause weights. In this paper, we propose the first two approaches to structure learning for PSL. We introduce a greedy search-based algorithm and a novel optimization method that trade-off scalability and approximations to the structure learning problem in varying ways. The highly scalable optimization method combines data-driven generation of clauses with a piecewise pseudolikelihood (PPLL) objective that learns model structure by optimizing clause weights only once. We compare both methods across five real-world tasks, showing that PPLL achieves an order of magnitude runtime speedup and AUC gains up to 15% over greedy search.

##### Abstract (translated by Google)
诸如马尔可夫逻辑网络和概率软逻辑（PSL）之类的统计关系框架使用加权的一阶逻辑子句来编码模型结构。从数据中学习这些条款称为结构学习。结构学习减轻了指定模型的手动成本。然而，这种好处伴随着高计算成本;结构学习通常需要在子句空间上进行昂贵的搜索，这涉及重复优化子句权重。在本文中，我们提出了PSL结构学习的前两种方法。我们介绍了一种基于搜索的贪婪算法和一种新颖的优化方法，它以不同的方式权衡可扩展性和结构学习问题的近似。高度可扩展的优化方法将数据驱动的子句生成与分段伪似然（PPLL）目标相结合，该目标通过仅优化子句权重一次来学习模型结构。我们比较了五种实际任务中的两种方法，表明PPLL实现了一个数量级的运行时加速，AUC比贪婪搜索提高了15％。

##### URL
[http://arxiv.org/abs/1807.00973](http://arxiv.org/abs/1807.00973)

##### PDF
[http://arxiv.org/pdf/1807.00973](http://arxiv.org/pdf/1807.00973)

