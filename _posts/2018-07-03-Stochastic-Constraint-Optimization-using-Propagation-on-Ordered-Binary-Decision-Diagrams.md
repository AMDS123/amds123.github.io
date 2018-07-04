---
layout: post
title: "Stochastic Constraint Optimization using Propagation on Ordered Binary Decision Diagrams"
date: 2018-07-03 10:58:38
categories: arXiv_AI
tags: arXiv_AI Optimization Relation
author: Anna L.D. Latour, Behrouz Babaki, Siegfried Nijssen
mathjax: true
---

* content
{:toc}

##### Abstract
A number of problems in relational Artificial Intelligence can be viewed as Stochastic Constraint Optimization Problems (SCOPs). These are constraint optimization problems that involve objectives or constraints with a stochastic component. Building on the recently proposed language SC-ProbLog for modeling SCOPs, we propose a new method for solving these problems. Earlier methods used Probabilistic Logic Programming (PLP) techniques to create Ordered Binary Decision Diagrams (OBDDs), which were decomposed into smaller constraints in order to exploit existing constraint programming (CP) solvers. We argue that this approach has as drawback that a decomposed representation of an OBDD does not guarantee domain consistency during search, and hence limits the efficiency of the solver. For the specific case of monotonic distributions, we suggest an alternative method for using CP in SCOP, based on the development of a new propagator; we show that this propagator is linear in the size of the OBDD, and has the potential to be more efficient than the decomposition method, as it maintains domain consistency.

##### Abstract (translated by Google)
关系人工智能中的许多问题可以被视为随机约束优化问题（SCOP）。这些是约束优化问题，其涉及具有随机分量的目标或约束。在最近提出的用于建模SCOP的语言SC-ProbLog的基础上，我们提出了一种解决这些问题的新方法。早期的方法使用概率逻辑编程（PLP）技术来创建有序二进制决策图（OBDD），它们被分解为更小的约束以便利用现有的约束编程（CP）求解器。我们认为这种方法的缺点是OBDD的分解表示不能保证搜索期间的域一致性，因此限制了求解器的效率。对于单调分布的具体情况，我们建议在SCOP中使用CP的另一种方法，基于新传播器的开发;我们证明了这个传播器在OBDD的大小上是线性的，并且有可能比分解方法更有效，因为它保持了域的一致性。

##### URL
[http://arxiv.org/abs/1807.01079](http://arxiv.org/abs/1807.01079)

##### PDF
[http://arxiv.org/pdf/1807.01079](http://arxiv.org/pdf/1807.01079)

