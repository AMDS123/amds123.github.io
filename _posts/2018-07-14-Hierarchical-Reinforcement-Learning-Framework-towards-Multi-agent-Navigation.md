---
layout: post
title: "Hierarchical Reinforcement Learning Framework towards Multi-agent Navigation"
date: 2018-07-14 18:07:32
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning
author: Wenhao Ding, Shuaijun Li, Huihuan Qian
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a navigation algorithm ori- ented to multi-agent dynamic environment. The algorithm is expressed as a hierarchical framework which contains a Hidden Markov Model (HMM) and Deep Reinforcement Learning (DRL). For simplification, we term our method Hierarchical Navigation Reinforcement Network (HNRN). In high-level architecture, we train an HMM to evaluate agents environment in order to obtain a score. According to this score, adaptive control action will be chosen. While in low-level architecture, two sub-systems are introduced, one is a differential target-driven system, which aims at heading to the target, the other is collision avoidance DRL system, which is used for avoiding obstacles in the dynamic environment. The advantage of this hierarchical system is to decouple the target-driven and collision avoidance tasks, leading to a faster and easier model to be trained. As the experiments manifest, our algorithm has faster learning efficiency and a higher success rate than traditional Velocity Obstacle (VO) algorithms and hybrid DRL method.

##### Abstract (translated by Google)
本文提出了一种定位于多智能体动态环境的导航算法。该算法表示为包含隐马尔可夫模型（HMM）和深度强化学习（DRL）的分层框架。为简化起见，我们称之为分层导航加固网络（HNRN）。在高级架构中，我们训练HMM来评估代理环境以获得分数。根据该分数，将选择自适应控制动作。在低层架构中，引入了两个子系统，一个是差分目标驱动系统，其目标是前往目标，另一个是防撞DRL系统，用于避开动态环境中的障碍。这种分层系统的优点是可以解除目标驱动和碰撞避免任务，从而可以更快，更轻松地训练模型。实验表明，与传统的速度障碍（VO）算法和混合DRL算法相比，我们的算法具有更快的学习效率和更高的成功率。

##### URL
[http://arxiv.org/abs/1807.05424](http://arxiv.org/abs/1807.05424)

##### PDF
[http://arxiv.org/pdf/1807.05424](http://arxiv.org/pdf/1807.05424)

