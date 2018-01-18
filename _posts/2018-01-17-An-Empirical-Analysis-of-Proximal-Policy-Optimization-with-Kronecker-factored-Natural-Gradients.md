---
layout: post
title: "An Empirical Analysis of Proximal Policy Optimization with Kronecker-factored Natural Gradients"
date: 2018-01-17 06:09:09
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Jiaming Song, Yuhuai Wu
mathjax: true
---

* content
{:toc}

##### Abstract
In this technical report, we consider an approach that combines the PPO objective and K-FAC natural gradient optimization, for which we call PPOKFAC. We perform a range of empirical analysis on various aspects of the algorithm, such as sample complexity, training speed, and sensitivity to batch size and training epochs. We observe that PPOKFAC is able to outperform PPO in terms of sample complexity and speed in a range of MuJoCo environments, while being scalable in terms of batch size. In spite of this, it seems that adding more epochs is not necessarily helpful for sample efficiency, and PPOKFAC seems to be worse than its A2C counterpart, ACKTR.

##### Abstract (translated by Google)
在这份技术报告中，我们考虑一种将PPO目标和K-FAC自然梯度优化相结合的方法，我们称之为PPOKFAC。我们对算法的各个方面进行了一系列的实证分析，如样本复杂度，训练速度以及对批量大小和训练时期的敏感度。我们观察到PPOKFAC在MuJoCo环境中的样本复杂度和速度方面能够胜过PPO，同时在批量方面可以扩展。尽管如此，似乎增加更多的时代对样本效率并不一定有帮助，而且PPOKFAC似乎比其A2C副本ACKTR更差。

##### URL
[http://arxiv.org/abs/1801.05566](http://arxiv.org/abs/1801.05566)

##### PDF
[http://arxiv.org/pdf/1801.05566](http://arxiv.org/pdf/1801.05566)

