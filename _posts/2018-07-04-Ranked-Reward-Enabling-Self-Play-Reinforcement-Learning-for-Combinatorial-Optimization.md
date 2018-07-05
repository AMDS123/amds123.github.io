---
layout: post
title: "Ranked Reward: Enabling Self-Play Reinforcement Learning for Combinatorial Optimization"
date: 2018-07-04 16:40:53
categories: arXiv_AI
tags: arXiv_AI Adversarial Reinforcement_Learning Optimization
author: Alexandre Laterre, Yunguan Fu, Mohamed Khalil Jabri, Alain-Sam Cohen, David Kas, Karl Hajjar, Torbjorn S. Dahl, Amine Kerkeni, Karim Beguir
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial self-play in two-player games has delivered impressive results when used with reinforcement learning algorithms that combine deep neural networks and tree search. Algorithms like AlphaZero and Expert Iteration learn tabula-rasa, producing highly informative training data on the fly. However, the self-play training strategy is not directly applicable to single-player games. Recently, several practically important combinatorial optimization problems, such as the traveling salesman problem and the bin packing problem, have been reformulated as reinforcement learning problems, increasing the importance of enabling the benefits of self-play beyond two-player games. We present the Ranked Reward (R2) algorithm which accomplishes this by ranking the rewards obtained by a single agent over multiple games to create a relative performance metric. Results from applying the R2 algorithm to instances of a two-dimensional bin packing problem show that it outperforms generic Monte Carlo tree search, heuristic algorithms and reinforcement learning algorithms not using ranked rewards.

##### Abstract (translated by Google)
当与结合深度神经网络和树搜索的强化学习算法一起使用时，双人游戏中的对抗性自我游戏已经产生了令人印象深刻的结果。 AlphaZero和Expert Iteration等算法可以学习tabula-rasa，即时生成信息丰富的培训数据。然而，自我游戏训练策略并不直接适用于单人游戏。最近，几个实际上重要的组合优化问题，例如旅行商问题和垃圾箱包装问题，被重新定义为强化学习问题，增加了实现超玩双人游戏之外的自我游戏的益处的重要性。我们提出了排名奖励（R2）算法，该算法通过对单个代理在多个游戏上获得的奖励进行排名来创建相对性能指标来实现这一点。将R2算法应用于二维bin打包问题的实例的结果表明，它优于通用蒙特卡罗树搜索，启发式算法和不使用排名奖励的强化学习算法。

##### URL
[http://arxiv.org/abs/1807.01672](http://arxiv.org/abs/1807.01672)

##### PDF
[http://arxiv.org/pdf/1807.01672](http://arxiv.org/pdf/1807.01672)

