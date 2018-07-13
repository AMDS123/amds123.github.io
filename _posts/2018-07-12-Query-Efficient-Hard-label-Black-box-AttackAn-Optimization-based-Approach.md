---
layout: post
title: "Query-Efficient Hard-label Black-box Attack:An Optimization-based Approach"
date: 2018-07-12 08:04:27
categories: arXiv_AI
tags: arXiv_AI CNN Optimization
author: Minhao Cheng, Thong Le, Pin-Yu Chen, Jinfeng Yi, Huan Zhang, Cho-Jui Hsieh
mathjax: true
---

* content
{:toc}

##### Abstract
We study the problem of attacking a machine learning model in the hard-label black-box setting, where no model information is revealed except that the attacker can make queries to probe the corresponding hard-label decisions. This is a very challenging problem since the direct extension of state-of-the-art white-box attacks (e.g., CW or PGD) to the hard-label black-box setting will require minimizing a non-continuous step function, which is combinatorial and cannot be solved by a gradient-based optimizer. The only current approach is based on random walk on the boundary, which requires lots of queries and lacks convergence guarantees. We propose a novel way to formulate the hard-label black-box attack as a real-valued optimization problem which is usually continuous and can be solved by any zeroth order optimization algorithm. For example, using the Randomized Gradient-Free method, we are able to bound the number of iterations needed for our algorithm to achieve stationary points. We demonstrate that our proposed method outperforms the previous random walk approach to attacking convolutional neural networks on MNIST, CIFAR, and ImageNet datasets. More interestingly, we show that the proposed algorithm can also be used to attack other discrete and non-continuous machine learning models, such as Gradient Boosting Decision Trees (GBDT).

##### Abstract (translated by Google)
我们研究了在硬标签黑盒设置中攻击机器学习模型的问题，其中没有显示模型信息，除了攻击者可以进行查询以探测相应的硬标签决策。这是一个非常具有挑战性的问题，因为将最先进的白盒攻击（例如，CW或PGD）直接扩展到硬标签黑盒设置将需要最小化非连续步进功能，这是组合并且不能通过基于梯度的优化器来解决。目前唯一的方法是基于边界上的随机游走，这需要大量的查询并且缺乏收敛保证。我们提出了一种新的方法来将硬标签黑盒攻击形成为实值优化问题，该问题通常是连续的并且可以通过任何零阶优化算法来解决。例如，使用Randomized Gradient-Free方法，我们能够限制算法实现静止点所需的迭代次数。我们证明了我们提出的方法优于先前的随机游走方法来攻击MNIST，CIFAR和ImageNet数据集上的卷积神经网络。更有趣的是，我们证明了所提出的算法还可以用于攻击其他离散和非连续机器学习模型，例如梯度提升决策树（GBDT）。

##### URL
[http://arxiv.org/abs/1807.04457](http://arxiv.org/abs/1807.04457)

##### PDF
[http://arxiv.org/pdf/1807.04457](http://arxiv.org/pdf/1807.04457)

