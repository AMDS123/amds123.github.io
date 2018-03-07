---
layout: post
title: "Intent-aware Multi-agent Reinforcement Learning"
date: 2018-03-06 04:53:50
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning Prediction
author: Siyuan Qi, Song-Chun Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes an intent-aware multi-agent planning framework as well as a learning algorithm. Under this framework, an agent plans in the goal space to maximize the expected utility. The planning process takes the belief of other agents' intents into consideration. Instead of formulating the learning problem as a partially observable Markov decision process (POMDP), we propose a simple but effective linear function approximation of the utility function. It is based on the observation that for humans, other people's intents will pose an influence on our utility for a goal. The proposed framework has several major advantages: i) it is computationally feasible and guaranteed to converge. ii) It can easily integrate existing intent prediction and low-level planning algorithms. iii) It does not suffer from sparse feedbacks in the action space. We experiment our algorithm in a real-world problem that is non-episodic, and the number of agents and goals can vary over time. Our algorithm is trained in a scene in which aerial robots and humans interact, and tested in a novel scene with a different environment. Experimental results show that our algorithm achieves the best performance and human-like behaviors emerge during the dynamic process.

##### Abstract (translated by Google)
本文提出了一个意图感知的多智能体规划框架以及一个学习算法。在此框架下，代理商计划在目标空间中最大化预期效用。规划过程考虑到其他代理商的意图。我们提出了一种简单而有效的线性函数逼近效用函数的方法，而不是将学习问题表述为部分可观察的马尔可夫决策过程（POMDP）。它基于对人类的观察，其他人的意图将对我们的目标的实用性产生影响。所提出的框架具有几个主要优点：i）它在计算上是可行的并且保证了收敛。 ii）它可以轻松地整合现有的意图预测和低级别规划算法。 iii）在行动空间中不会遭受稀疏的反馈。我们在一个非偶发现实世界的问题中试验我们的算法，并且代理和目标的数量随着时间的推移而变化。我们的算法在空中机器人和人类交互的场景中进行训练，并在具有不同环境的新景中进行测试。实验结果表明，我们的算法达到了最佳性能，并且在动态过程中出现了类似人的行为。

##### URL
[http://arxiv.org/abs/1803.02018](http://arxiv.org/abs/1803.02018)

##### PDF
[http://arxiv.org/pdf/1803.02018](http://arxiv.org/pdf/1803.02018)

