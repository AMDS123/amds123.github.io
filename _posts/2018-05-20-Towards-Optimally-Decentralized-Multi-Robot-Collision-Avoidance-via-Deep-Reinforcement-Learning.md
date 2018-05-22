---
layout: post
title: "Towards Optimally Decentralized Multi-Robot Collision Avoidance via Deep Reinforcement Learning"
date: 2018-05-20 08:36:24
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning
author: Pinxin Long, Tingxiang Fan, Xinyi Liao, Wenxi Liu, Hao Zhang, Jia Pan
mathjax: true
---

* content
{:toc}

##### Abstract
Developing a safe and efficient collision avoidance policy for multiple robots is challenging in the decentralized scenarios where each robot generate its paths without observing other robots' states and intents. While other distributed multi-robot collision avoidance systems exist, they often require extracting agent-level features to plan a local collision-free action, which can be computationally prohibitive and not robust. More importantly, in practice the performance of these methods are much lower than their centralized counterparts. 
 We present a decentralized sensor-level collision avoidance policy for multi-robot systems, which directly maps raw sensor measurements to an agent's steering commands in terms of movement velocity. As a first step toward reducing the performance gap between decentralized and centralized methods, we present a multi-scenario multi-stage training framework to find an optimal policy which is trained over a large number of robots on rich, complex environments simultaneously using a policy gradient based reinforcement learning algorithm. We validate the learned sensor-level collision avoidance policy in a variety of simulated scenarios with thorough performance evaluations and show that the final learned policy is able to find time efficient, collision-free paths for a large-scale robot system. We also demonstrate that the learned policy can be well generalized to new scenarios that do not appear in the entire training period, including navigating a heterogeneous group of robots and a large-scale scenario with 100 robots. Videos are available at https://sites.google.com/view/drlmaca

##### Abstract (translated by Google)
针对多个机器人制定安全和有效的避撞策略在每个机器人在不观察其他机器人的状态和意图的情况下生成其路径的分散场景中具有挑战性。虽然存在其他分布式多机器人碰撞避免系统，但它们通常需要提取代理级别的特征来规划本地无碰撞行为，这可能会在计算上受到限制并且不健壮。更重要的是，在实践中，这些方法的表现远远低于其集中对应的表现。
 我们提出了一个多机器人系统的分散式传感器级避免碰撞策略，它将原始传感器测量结果直接映射到代理人的转向命令的运动速度。作为减少分散式和集中式方法之间性能差距的第一步，我们提出了一个多场景多阶段培训框架，以找到一个最优策略，该策略在丰富，复杂的环境中通过大量机器人同时使用策略梯度基于强化学习算法。我们通过全面的性能评估在各种模拟场景中验证学习到的传感器级别碰撞避免策略，并显示最终的学习策略能够为大型机器人系统找到时间有效的无碰撞路径。我们还证明，学习策略可以很好地推广到整个培训阶段未出现的新情况，包括导航一组机器人，以及包含100个机器人的大型场景。视频可在https://sites.google.com/view/drlmaca上找到

##### URL
[http://arxiv.org/abs/1709.10082](http://arxiv.org/abs/1709.10082)

##### PDF
[http://arxiv.org/pdf/1709.10082](http://arxiv.org/pdf/1709.10082)

