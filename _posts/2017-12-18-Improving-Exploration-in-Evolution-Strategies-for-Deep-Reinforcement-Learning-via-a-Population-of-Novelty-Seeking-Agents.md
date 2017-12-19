---
layout: post
title: "Improving Exploration in Evolution Strategies for Deep Reinforcement Learning via a Population of Novelty-Seeking Agents"
date: 2017-12-18 18:10:39
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning Optimization
author: Edoardo Conti, Vashisht Madhavan, Felipe Petroski Such, Joel Lehman, Kenneth O. Stanley, Jeff Clune
mathjax: true
---

* content
{:toc}

##### Abstract
Evolution strategies (ES) are a family of black-box optimization algorithms able to train deep neural networks roughly as well as Q-learning and policy gradient methods on challenging deep reinforcement learning (RL) problems, but are much faster (e.g. hours vs. days) because they parallelize better. However, many RL problems require directed exploration because they have reward functions that are sparse or deceptive (i.e. contain local optima), and it is not known how to encourage such exploration with ES. Here we show that algorithms that have been invented to promote directed exploration in small-scale evolved neural networks via populations of exploring agents, specifically novelty search (NS) and quality diversity (QD) algorithms, can be hybridized with ES to improve its performance on sparse or deceptive deep RL tasks, while retaining scalability. Our experiments confirm that the resultant new algorithms, NS-ES and a version of QD we call NSR-ES, avoid local optima encountered by ES to achieve higher performance on tasks ranging from playing Atari to simulated robots learning to walk around a deceptive trap. This paper thus introduces a family of fast, scalable algorithms for reinforcement learning that are capable of directed exploration. It also adds this new family of exploration algorithms to the RL toolbox and raises the interesting possibility that analogous algorithms with multiple simultaneous paths of exploration might also combine well with existing RL algorithms outside ES.

##### Abstract (translated by Google)
进化策略（ES）是一套黑盒子优化算法，能够粗略地训练深度神经网络，以及针对具有挑战性的深度强化学习（RL）问题的Q学习和策略梯度方法，但速度更快（例如小时vs.天），因为它们并行更好。然而，许多RL问题需要有针对性的探索，因为它们具有稀疏或欺骗性的回报功能（即包含局部最优），并且不知道如何用ES来鼓励这种探索。在这里，我们表明，已发明的算法，以促进定向探索小规模进化神经网络通过探索代理人群，特别是新颖性搜索（NS）和质量多样性（QD）算法，可以与ES杂交，以改善其性能稀疏或欺骗性的深层RL任务，同时保持可扩展性。我们的实验证实，由此产生的新算法NS-ES和我们称之为NSR-ES的QD版本避免了ES遇到的局部最优性能，从玩Atari到模拟机器人学习绕过一个欺骗性陷阱的任务，实现了更高的性能。因此，本文介绍了一系列快速，可扩展的强化学习算法，能够进行有针对性的探索。它还将这个新的探索算法家族添加到RL工具箱，并提出了一个有趣的可能性，即具有多个同时探索路径的类似算法也可以与ES以外的现有RL算法很好地结合。

##### URL
[http://arxiv.org/abs/1712.06560](http://arxiv.org/abs/1712.06560)

##### PDF
[http://arxiv.org/pdf/1712.06560](http://arxiv.org/pdf/1712.06560)

