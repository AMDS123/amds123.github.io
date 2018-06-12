---
layout: post
title: "Assumed Density Filtering Q-learning"
date: 2018-06-11 03:22:06
categories: arXiv_AI
tags: arXiv_AI Regularization Reinforcement_Learning Inference
author: Heejin Jeong, Clark Zhang, Daniel D. Lee
mathjax: true
---

* content
{:toc}

##### Abstract
While off-policy temporal difference (TD) methods have widely been used in reinforcement learning due to their efficiency and simple implementation, their Bayesian counterparts have not been utilized as frequently. One reason is that the non-linear max operation in the Bellman optimality equation makes it difficult to define conjugate distributions over the value functions. In this paper, we introduce a novel Bayesian approach to off-policy TD methods using Assumed Density Filtering (ADFQ), which updates beliefs on state-action values (Q) through an online Bayesian inference method. Uncertainty measures in the beliefs provide a natural regularization for learning, and we show how ADFQ reduces in a limiting case to the traditional Q-learning algorithm. Our empirical results demonstrate that the proposed ADFQ algorithms outperform comparable algorithms on several task domains. Moreover, our algorithms are computationally more efficient than other existing approaches to Bayesian reinforcement learning.

##### Abstract (translated by Google)
虽然由于效率高且实施简单，非政策时差（TD）方法广泛用于强化学习，但它们的贝叶斯方法并未经常使用。原因之一是Bellman最优性方程中的非线性最大运算使得定义整个值函数的共轭分布变得困难。在本文中，我们介绍了一种新的贝叶斯方法，采用假设密度过滤（ADFQ），通过在线贝叶斯推理方法更新对状态动作值（Q）的信念。信念中的不确定性度量为学习提供了一种自然的正则化，并且我们展示了ADFQ如何在极限情况下减少到传统的Q学习算法。我们的实证结果表明，所提出的ADFQ算法在几个任务域上胜过可比较的算法。此外，我们的算法在计算上比其他现有的贝叶斯强化学习方法更有效。

##### URL
[http://arxiv.org/abs/1712.03333](http://arxiv.org/abs/1712.03333)

##### PDF
[http://arxiv.org/pdf/1712.03333](http://arxiv.org/pdf/1712.03333)

