---
layout: post
title: "Sampled Policy Gradient for Learning to Play the Game Agar.io"
date: 2018-09-15 20:01:06
categories: arXiv_AI
tags: arXiv_AI
author: Anton Orell Wiehe, Nil Stolt Ans&#xf3;, Madalina M. Drugan, Marco A. Wiering
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, a new offline actor-critic learning algorithm is introduced: Sampled Policy Gradient (SPG). SPG samples in the action space to calculate an approximated policy gradient by using the critic to evaluate the samples. This sampling allows SPG to search the action-Q-value space more globally than deterministic policy gradient (DPG), enabling it to theoretically avoid more local optima. SPG is compared to Q-learning and the actor-critic algorithms CACLA and DPG in a pellet collection task and a self play environment in the game Agar.io. The online game Agar.io has become massively popular on the internet due to intuitive game design and the ability to instantly compete against players around the world. From the point of view of artificial intelligence this game is also very intriguing: The game has a continuous input and action space and allows to have diverse agents with complex strategies compete against each other. The experimental results show that Q-Learning and CACLA outperform a pre-programmed greedy bot in the pellet collection task, but all algorithms fail to outperform this bot in a fighting scenario. The SPG algorithm is analyzed to have great extendability through offline exploration and it matches DPG in performance even in its basic form without extensive sampling.

##### Abstract (translated by Google)
在本文中，介绍了一种新的离线演员批评学习算法：采样策略梯度（SPG）。动作空间中的SPG样本通过使用评论家来评估样本来计算近似的策略梯度。该抽样允许SPG比确定性策略梯度（DPG）更全局地搜索动作Q值空间，使其理论上能够避免更多的局部最优。 SPG与粒子收集任务中的Q学习和演员评论算法CACLA和DPG以及游戏Agar.io中的自我游戏环境进行了比较。由于直观的游戏设计和即时与世界各地的玩家竞争的能力，在线游戏Agar.io已经在互联网上大受欢迎。从人工智能的角度来看，这个游戏也非常有趣：游戏具有连续的输入和动作空间，并允许具有复杂策略的不同代理相互竞争。实验结果表明，Q-Learning和CACLA在颗粒收集任务中的表现优于预编程的贪婪机器人，但所有算法在战斗情景中都无法胜过这个机器人。通过离线探索分析SPG算法具有很好的可扩展性，即使在基本形式下也可以匹配DPG的性能而无需大量采样。

##### URL
[http://arxiv.org/abs/1809.05763](http://arxiv.org/abs/1809.05763)

##### PDF
[http://arxiv.org/pdf/1809.05763](http://arxiv.org/pdf/1809.05763)

