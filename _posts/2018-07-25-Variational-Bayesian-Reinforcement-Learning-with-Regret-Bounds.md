---
layout: post
title: "Variational Bayesian Reinforcement Learning with Regret Bounds"
date: 2018-07-25 14:56:09
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Brendan O&#x27;Donoghue
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the exploration-exploitation trade-off in reinforcement learning and we show that an agent imbued with a risk-seeking utility function is able to explore efficiently, as measured by regret. The parameter that controls how risk-seeking the agent is can be optimized exactly, or annealed according to a schedule. We call the resulting algorithm K-learning and show that the corresponding K-values are optimistic for the expected Q-values at each state-action pair. The K-values induce a natural Boltzmann exploration policy for which the `temperature' parameter is equal to the risk-seeking parameter. This policy achieves an expected regret bound of $\tilde O(L^{3/2} \sqrt{S A T})$, where $L$ is the time horizon, $S$ is the number of states, $A$ is the number of actions, and $T$ is the total number of elapsed time-steps. This bound is only a factor of $L$ larger than the established lower bound. K-learning can be interpreted as mirror descent in the policy space, and it is similar to other well-known methods in the literature, including Q-learning, soft-Q-learning, and maximum entropy policy gradient, and is closely related to optimism and count based exploration methods. K-learning is simple to implement, as it only requires adding a bonus to the reward at each state-action and then solving a Bellman equation. We conclude with a numerical example demonstrating that K-learning is competitive with other state-of-the-art algorithms in practice.

##### Abstract (translated by Google)
我们考虑在强化学习中进行勘探 - 开发权衡，并且我们表明，充满风险寻求效用函数的代理人能够有效地进行探索，遗憾的是。控制代理人寻求风险的方式的参数可以精确优化，也可以根据时间表退火。我们将得到的算法K学习称为并且表明相应的K值对于每个状态 - 动作对的预期Q值是乐观的。 K值引发了一个自然的玻尔兹曼探索策略，其“温度”参数等于寻求风险的参数。此政策实现了$ \ tilde O（L ^ {3/2} \ sqrt {SAT}）$的预期后悔限制，其中$ L $是时间范围，$ S $是州的数量，$ A $是操作数，$ T $是已用时间步数的总和。这个界限只比建立的下限大$ L $。 K学习可以解释为政策空间中的镜像下降，它类似于文献中其他众所周知的方法，包括Q学习，软Q学习和最大熵策略梯度，并且与基于乐观和计数的探索方法。 K学习很容易实现，因为它只需要在每个状态动作中为奖励添加奖励，然后解决Bellman等式。最后，我们用一个数值例子来证明K-learning在实践中与其他最先进的算法相比具有竞争力。

##### URL
[http://arxiv.org/abs/1807.09647](http://arxiv.org/abs/1807.09647)

##### PDF
[http://arxiv.org/pdf/1807.09647](http://arxiv.org/pdf/1807.09647)

