---
layout: post
title: "Is Q-learning Provably Efficient?"
date: 2018-07-10 17:21:35
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning
author: Chi Jin, Zeyuan Allen-Zhu, Sebastien Bubeck, Michael I. Jordan
mathjax: true
---

* content
{:toc}

##### Abstract
Model-free reinforcement learning (RL) algorithms, such as Q-learning, directly parameterize and update value functions or policies without explicitly modeling the environment. They are typically simpler, more flexible to use, and thus more prevalent in modern deep RL than model-based approaches. However, empirical work has suggested that model-free algorithms may require more samples to learn [Deisenroth and Rasmussen 2011, Schulman et al. 2015]. The theoretical question of "whether model-free algorithms can be made sample efficient" is one of the most fundamental questions in RL, and remains unsolved even in the basic scenario with finitely many states and actions. 
 We prove that, in an episodic MDP setting, Q-learning with UCB exploration achieves regret $\tilde{O}(\sqrt{H^3 SAT})$, where $S$ and $A$ are the numbers of states and actions, $H$ is the number of steps per episode, and $T$ is the total number of steps. This sample efficiency matches the optimal regret that can be achieved by any model-based approach, up to a single $\sqrt{H}$ factor. To the best of our knowledge, this is the first analysis in the model-free setting that establishes $\sqrt{T}$ regret without requiring access to a "simulator."

##### Abstract (translated by Google)
无模型强化学习（RL）算法（如Q-learning）可直接参数化和更新值函数或策略，而无需对环境进行明确建模。它们通常更简单，使用更灵活，因此在现代深度RL中比基于模型的方法更普遍。然而，实证研究表明，无模型算法可能需要更多的样本来学习[Deisenroth和Rasmussen 2011，Schulman等。 2015年]。 “无模型算法是否可以使样本有效”的理论问题是RL中最基本的问题之一，即使在有限许多状态和动作的基本场景中仍未解决。
 我们证明，在一个简短的MDP设置中，UCB探索的Q学习实现后悔$ \ tilde {O}（\ sqrt {H ^ 3 SAT}）$，其中$ S $和$ A $是州和动作，$ H $是每集的步数，$ T $是总步数。此样本效率与任何基于模型的方法可达到的最佳后悔相匹配，最高可达单个$ \ sqrt {H} $因子。据我们所知，这是无模型设置中的第一个分析，它建立$ \ sqrt {T} $后悔而无需访问“模拟器”。

##### URL
[http://arxiv.org/abs/1807.03765](http://arxiv.org/abs/1807.03765)

##### PDF
[http://arxiv.org/pdf/1807.03765](http://arxiv.org/pdf/1807.03765)

