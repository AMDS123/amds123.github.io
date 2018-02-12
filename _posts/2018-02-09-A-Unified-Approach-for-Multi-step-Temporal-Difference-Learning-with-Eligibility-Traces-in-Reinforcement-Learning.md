---
layout: post
title: "A Unified Approach for Multi-step Temporal-Difference Learning with Eligibility Traces in Reinforcement Learning"
date: 2018-02-09 08:46:21
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Long Yang, Minhao Shi, Qian Zheng, Wenjia Meng, Gang Pan
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, a new multi-step temporal learning algorithm, called $Q(\sigma)$, unifies $n$-step Tree-Backup (when $\sigma=0$) and $n$-step Sarsa (when $\sigma=1$) by introducing a sampling parameter $\sigma$. However, similar to other multi-step temporal-difference learning algorithms, $Q(\sigma)$ needs much memory consumption and computation time. Eligibility trace is an important mechanism to transform the off-line updates into efficient on-line ones which consume less memory and computation time. In this paper, we further develop the original $Q(\sigma)$, combine it with eligibility traces and propose a new algorithm, called $Q(\sigma ,\lambda)$, in which $\lambda$ is trace-decay parameter. This idea unifies Sarsa$(\lambda)$ (when $\sigma =1$) and $Q^{\pi}(\lambda)$ (when $\sigma =0$). Furthermore, we give an upper error bound of $Q(\sigma ,\lambda)$ policy evaluation algorithm. We prove that $Q(\sigma,\lambda)$ control algorithm can converge to the optimal value function exponentially. We also empirically compare it with conventional temporal-difference learning methods. Results show that, with an intermediate value of $\sigma$, $Q(\sigma ,\lambda)$ creates a mixture of the existing algorithms that can learn the optimal value significantly faster than the extreme end ($\sigma=0$, or $1$).

##### Abstract (translated by Google)
最近，一种称为$ Q（\ sigma）$的新的多步时间学习算法将$ n $ -step Tree-Backup（当$ \ sigma = 0 $时）和$ n $ -step Sarsa（当$ \ sigma = 1 $）通过引入抽样参数$ \ sigma $。然而，与其他多步骤时间差分学习算法类似，$ Q（\ sigma）$需要大量的内存消耗和计算时间。资格跟踪是将离线更新转换为高效的在线消息的重要机制，消耗更少的内存和计算时间。在本文中，我们进一步开发原始的$ Q（\ sigma）$，将它与资格痕迹结合起来，并提出一种新的算法，称为$ Q（\ sigma，\ lambda）$，其中$ \ lambda $是trace-decay参数。这个想法统一了Sarsa $（\ lambda）$（当$ \ sigma = 1 $）和$ Q ^ {\ pi}（\ lambda）$（当$ \ sigma = 0 $时）。此外，我们给出了$ Q（\ sigma，\ lambda）$策略评估算法的上限误差。证明$ Q（\ sigma，\ lambda）$控制算法可以指数函数收敛到最优值函数。我们还将它与传统的时间差分学习方法进行了实证比较。结果表明，在$ \ sigma $的中间值的情况下，$ Q（\ sigma，\ lambda）$创建了一个混合的现有算法，可以比极端（$ \ sigma = 0 $ ，或$ 1 $）。

##### URL
[http://arxiv.org/abs/1802.03171](http://arxiv.org/abs/1802.03171)

##### PDF
[http://arxiv.org/pdf/1802.03171](http://arxiv.org/pdf/1802.03171)

