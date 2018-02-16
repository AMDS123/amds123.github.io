---
layout: post
title: "Reinforcement Learning from Imperfect Demonstrations"
date: 2018-02-14 20:37:38
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Yang Gao, Huazhe (Harry)Xu, Ji Lin, Fisher Yu, Sergey Levine, Trevor Darrell
mathjax: true
---

* content
{:toc}

##### Abstract
Robust real-world learning should benefit from both demonstrations and interactions with the environment. Current approaches to learning from demonstration and reward perform supervised learning on expert demonstration data and use reinforcement learning to further improve performance based on the reward received from the environment. These tasks have divergent losses which are difficult to jointly optimize and such methods can be very sensitive to noisy demonstrations. We propose a unified reinforcement learning algorithm, Normalized Actor-Critic (NAC), that effectively normalizes the Q-function, reducing the Q-values of actions unseen in the demonstration data. NAC learns an initial policy network from demonstrations and refines the policy in the environment, surpassing the demonstrator's performance. Crucially, both learning from demonstration and interactive refinement use the same objective, unlike prior approaches that combine distinct supervised and reinforcement losses. This makes NAC robust to suboptimal demonstration data since the method is not forced to mimic all of the examples in the dataset. We show that our unified reinforcement learning algorithm can learn robustly and outperform existing baselines when evaluated on several realistic driving games.

##### Abstract (translated by Google)
强大的现实世界学习应该受益于示范和与环境的相互作用。目前从示范和奖励中学习的方法对专家演示数据进行监督式学习，并使用强化学习来进一步提高基于来自环境的奖励的绩效。这些任务具有不同的损失，难以共同优化，并且这些方法可能对嘈杂的示范非常敏感。我们提出了一个统一的强化学习算法 - 归一化演员 - 评论家（NAC），它有效地规范了Q函数，减少了演示数据中看不见的行为的Q值。 NAC通过示威学习初步政策网络，并改善环境方面的政策，超过了示威者的表现。至关重要的是，从示范和交互式细化中学习都使用相同的目标，而不像以前的方法结合了不同的监督和钢筋损失。这使得NAC对欠佳的演示数据具有鲁棒性，因为该方法不会被迫模拟数据集中的所有示例。我们表明，我们的统一强化学习算法可以在几个逼真的驾驶游戏上进行评估时强健地学习并超越现有的基线。

##### URL
[http://arxiv.org/abs/1802.05313](http://arxiv.org/abs/1802.05313)

##### PDF
[http://arxiv.org/pdf/1802.05313](http://arxiv.org/pdf/1802.05313)

