---
layout: post
title: "Improving the Parallel Execution of Behavior Trees"
date: 2018-09-13 11:58:31
categories: arXiv_RO
tags: arXiv_RO
author: Michele Colledanchise, Lorenzo Natale
mathjax: true
---

* content
{:toc}

##### Abstract
Behavior Trees (BTs) have become a popular framework for designing controllers of autonomous agents in the computer game and in the robotics industry. One of the key advantages of BTs lies in their modularity, where independent modules can be composed to create more complex ones. In the classical formulation of BTs, modules can be composed using one of the three operators: Sequence, Fallback, and Parallel. The Parallel operator is rarely used despite its strong potential against other control architectures as Finite State Machines. This is due to the fact that concurrent actions may lead to unexpected problems similar to the ones experienced in concurrent programming. In this paper, we introduce Concurrent BTs (CBTs) as a generalization of BTs in which we introduce the notions of progress and resource usage. We show how CBTs allow safe concurrent executions of actions and we analyze the approach from a mathematical standpoint. To illustrate the use of CBTs, we provide a set of use cases in robotics scenarios.

##### Abstract (translated by Google)
行为树（BT）已经成为在计算机游戏和机器人行业中设计自主代理控制器的流行框架。 BT的一个关键优势在于它们的模块化，可以组成独立的模块来创建更复杂的模块。在BT的经典公式中，模块可以使用三个运算符中的一个来组成：序列，后退和并行。并行运算符很少使用，尽管其作为有限状态机的其他控制架构具有很强的潜力。这是因为并发操作可能导致类似于并发编程所遇到的意外问题。在本文中，我们引入并行BT（CBT）作为BT的概括，其中我们介绍了进展和资源使用的概念。我们展示了CBT如何允许安全地同时执行操作，并且我们从数学角度分析了该方法。为了说明CBT的使用，我们在机器人场景中提供了一组用例。

##### URL
[http://arxiv.org/abs/1809.04898](http://arxiv.org/abs/1809.04898)

##### PDF
[http://arxiv.org/pdf/1809.04898](http://arxiv.org/pdf/1809.04898)

