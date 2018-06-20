---
layout: post
title: "Unsupervised Basis Function Adaptation for Reinforcement Learning"
date: 2018-06-18 21:26:30
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Edward Barker, Charl Ras
mathjax: true
---

* content
{:toc}

##### Abstract
When using reinforcement learning (RL) algorithms it is common, given a large state space, to introduce some form of approximation architecture for the value function (VF). The exact form of this architecture can have a significant effect on an agent's performance, however, and determining a suitable approximation architecture can often be a highly complex task. Consequently there is currently interest among researchers in the potential for allowing RL algorithms to adaptively generate (i.e. to learn) approximation architectures. One relatively unexplored method of adapting approximation architectures involves using feedback regarding the frequency with which an agent has visited certain states to guide which areas of the state space to approximate with greater detail. In this article we will: (a) informally discuss the potential advantages offered by such methods; (b) introduce a new algorithm based on such methods which adapts a state aggregation approximation architecture on-line and is designed for use in conjunction with SARSA; (c) provide theoretical results, in a policy evaluation setting, regarding this particular algorithm's complexity, convergence properties and potential to reduce VF error; and finally (d) test experimentally the extent to which this algorithm can improve performance given a number of different test problems. Taken together our results suggest that our algorithm (and potentially such methods more generally) can provide a versatile and computationally lightweight means of significantly boosting RL performance given suitable conditions which are commonly encountered in practice.

##### Abstract (translated by Google)
当使用强化学习（RL）算法时，在给定大的状态空间的情况下，为值函数（VF）引入某种形式的逼近架构是很常见的。然而，这种体系结构的确切形式可能会对代理的性能产生重大影响，并且确定合适的近似体系结构往往是一项非常复杂的任务。因此，研究人员目前对允许RL算法自适应生成（即学习）近似体系结构的潜力感兴趣。适应近似体系结构的一种相对未探索的方法涉及使用关于代理访问某些状态的频率的反馈，以指导状态空间的哪些区域更详细地近似。在本文中，我们将：（a）非正式讨论这些方法提供的潜在优势; （b）引入一种基于这种方法的新算法，该方法在线调整状态聚合近似体系结构并设计为与SARSA结合使用; （c）在策略评估设置中提供关于该特定算法的复杂性，收敛特性和降低VF误差的可能性的理论结果;最后（d）通过实验测试该算法在多种不同的测试问题下可以提高性能的程度。综合考虑，我们的结果表明，我们的算法（以及更普遍地可能的这种方法）可以提供通用且计算轻量的手段，其在给定实践中通常遇到的适当条件的情况下显着提高RL性能。

##### URL
[http://arxiv.org/abs/1703.07940](http://arxiv.org/abs/1703.07940)

##### PDF
[http://arxiv.org/pdf/1703.07940](http://arxiv.org/pdf/1703.07940)

