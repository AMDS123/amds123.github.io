---
layout: post
title: "Fully Distributed Multi-Robot Collision Avoidance via Deep Reinforcement Learning for Safe and Efficient Navigation in Complex Scenarios"
date: 2018-08-11 17:33:40
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning
author: Tingxiang Fan, Pinxin Long, Wenxi Liu, Jia Pan
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a decentralized sensor-level collision avoidance policy for multi-robot systems, which shows promising results in practical applications. In particular, our policy directly maps raw sensor measurements to an agent's steering commands in terms of the movement velocity. As a first step toward reducing the performance gap between decentralized and centralized methods, we present a multi-scenario multi-stage training framework to learn an optimal policy. The policy is trained over a large number of robots in rich, complex environments simultaneously using a policy gradient based reinforcement learning algorithm. The learning algorithm is also integrated into a hybrid control framework to further improve the policy's robustness and effectiveness. 
 We validate the learned sensor-level collision avoidance policy in a variety of simulated and real-world scenarios with thorough performance evaluations for large-scale multi-robot systems. The generalization of the learned policy is verified in a set of unseen scenarios including the navigation of a group of heterogeneous robots and a large-scale scenario with 100 robots. Although the policy is trained using simulation data only, we have successfully deployed it on physical robots with shapes and dynamics characteristics that are different from the simulated agents, in order to demonstrate the controller's robustness against the sim-to-real modeling error. Finally, we show that the collision-avoidance policy learned from multi-robot navigation tasks provides an excellent solution to the safe and effective autonomous navigation for a single robot working in a dense real human crowd. Our learned policy enables a robot to make effective progress in a crowd without getting stuck. Videos are available at https://sites.google.com/view/hybridmrca

##### Abstract (translated by Google)
在本文中，我们提出了一种分散的传感器级碰撞避免策略，用于多机器人系统，在实际应用中显示出有希望的结果。特别是，我们的政策根据运动速度直接将原始传感器测量值映射到代理的转向命令。作为减少分散式和集中式方法之间性能差距的第一步，我们提出了一个多场景多阶段培训框架来学习最优策略。该策略使用基于策略梯度的强化学习算法同时在丰富，复杂的环境中训练大量机器人。学习算法也被集成到混合控制框架中，以进一步提高策略的稳健性和有效性。
 我们通过对大型多机器人系统的全面性能评估，在各种模拟和真实场景中验证所学习的传感器级碰撞避免策略。学习策略的概括在一组看不见的场景中得到验证，包括一组异构机器人的导航和一个包含100个机器人的大规模场景。尽管该策略仅使用模拟数据进行训练，但我们已成功将其部署在物理机器人上，其形状和动态特性与模拟代理不同，以展示控制器对模拟到实际建模错误的鲁棒性。最后，我们展示了从多机器人导航任务中学到的避碰策略为在密集的真实人群中工作的单个机器人提供了安全有效的自主导航的出色解决方案。我们学到的政策使机器人能够在人群中取得有效进展而不会卡住。有关视频，请访问https://sites.google.com/view/hybridmrca

##### URL
[http://arxiv.org/abs/1808.03841](http://arxiv.org/abs/1808.03841)

##### PDF
[http://arxiv.org/pdf/1808.03841](http://arxiv.org/pdf/1808.03841)

