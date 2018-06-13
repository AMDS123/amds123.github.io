---
layout: post
title: "Multi-step Reinforcement Learning: A Unifying Algorithm"
date: 2018-06-11 22:01:57
categories: arXiv_AI
tags: arXiv_AI GAN Reinforcement_Learning Prediction
author: Kristopher De Asis, J. Fernando Hernandez-Garcia, G. Zacharias Holland, Richard S. Sutton
mathjax: true
---

* content
{:toc}

##### Abstract
Unifying seemingly disparate algorithmic ideas to produce better performing algorithms has been a longstanding goal in reinforcement learning. As a primary example, TD($\lambda$) elegantly unifies one-step TD prediction with Monte Carlo methods through the use of eligibility traces and the trace-decay parameter $\lambda$. Currently, there are a multitude of algorithms that can be used to perform TD control, including Sarsa, $Q$-learning, and Expected Sarsa. These methods are often studied in the one-step case, but they can be extended across multiple time steps to achieve better performance. Each of these algorithms is seemingly distinct, and no one dominates the others for all problems. In this paper, we study a new multi-step action-value algorithm called $Q(\sigma)$ which unifies and generalizes these existing algorithms, while subsuming them as special cases. A new parameter, $\sigma$, is introduced to allow the degree of sampling performed by the algorithm at each step during its backup to be continuously varied, with Sarsa existing at one extreme (full sampling), and Expected Sarsa existing at the other (pure expectation). $Q(\sigma)$ is generally applicable to both on- and off-policy learning, but in this work we focus on experiments in the on-policy case. Our results show that an intermediate value of $\sigma$, which results in a mixture of the existing algorithms, performs better than either extreme. The mixture can also be varied dynamically which can result in even greater performance.

##### Abstract (translated by Google)
统一表面上不同的算法思想，以产生更好的执行算法，一直是强化学习的长期目标。作为一个主要的例子，TD（$ \ lambda $）通过使用资格追踪和追踪衰变参数$ \ lambda $，将一步TD预测与蒙特卡洛方法优雅地结合在一起。目前，有许多算法可用于执行TD控制，包括Sarsa，$ Q $ -learning和Expected Sarsa。这些方法通常在一步式的情况下进行研究，但是它们可以跨多个时间步骤进行扩展以实现更好的性能。这些算法中的每一个都看似不同，没有人为所有问题支配其他算法。在本文中，我们研究了一种称为$ Q（\ sigma）$的多步骤动作值算法，它将这些现有算法统一并进行了概括，同时将它们作为特殊情况归并。引入一个新参数$ \ sigma $，以允许算法在其备份期间的每个步骤进行的采样程度不断变化，Sarsa存在于一个极端（完整采样），另一个极端存在预期的Sarsa （纯粹的期望）。 $ Q（\ sigma）$通常适用于在线和离线学习，但在这项工作中，我们将重点放在政策案例的实验上。我们的结果显示$ \ sigma $的中间值导致现有算法的混合，表现比任何一个极端都好。混合物也可以动态变化，这可以产生更高的性能。

##### URL
[http://arxiv.org/abs/1703.01327](http://arxiv.org/abs/1703.01327)

##### PDF
[http://arxiv.org/pdf/1703.01327](http://arxiv.org/pdf/1703.01327)

