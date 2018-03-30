---
layout: post
title: "Learning Deep Policies for Physics-Based Manipulation in Clutter"
date: 2018-03-21 19:37:18
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning
author: Wissam Bejjani, Rafael Papallas, Matteo Leonetti, Mehmet R. Dogar
mathjax: true
---

* content
{:toc}

##### Abstract
Uncertainty in modeling real world physics makes transferring traditional open-loop motion planning techniques from simulation to the real world particularly challenging. Available closed-loop policy learning approaches, for physics-based manipulation tasks, typically either focus on single object manipulation, or rely on imitation learning, which inherently constrains task generalization and performance to the available demonstrations. In this work, we propose an approach to learn a policy for physics-based manipulation in clutter, which enables the robot to react to the uncertain dynamics of the real world. We start with presenting an imitation learning technique which compiles demonstrations from a sampling-based planner into an action-value function encoded as a deep neural network. We then use the learned action-value function to guide a look-ahead planner, giving us a control policy. Lastly, we propose to refine the deep action-value function through reinforcement learning, taking advantage of the look-ahead planner. We evaluate our approach in a physics-enabled simulation environment with artificially injected uncertainty, as well as in a real world task of manipulation in clutter.

##### Abstract (translated by Google)
对现实世界物理学建模的不确定性使得将传统的开环运动规划技术从仿真转移到现实世界尤其具有挑战性。对于基于物理学的操作任务，可用的闭环策略学习方法通​​常要么专注于单个对象操作，要么依赖于模仿学习，这本质上限制了任务泛化和性能的可用示范。在这项工作中，我们提出了一种方法来学习基于物理的杂波处理策略，使机器人能够对现实世界的不确定动态做出反应。我们首先介绍一种模仿学习技术，将基于抽样的策划者的演示编译成一个编码为深度神经网络的动作值函数。然后，我们使用学习的行动价值函数来指导先行计划者，给我们一个控制策略。最后，我们建议通过强化学习来改进深层次的行动价值函数，以利用先行计划者。我们在一个物理模拟环境中评估我们的方法，其中包含人为注入的不确定性以及现实世界中混乱操纵的任务。

##### URL
[https://arxiv.org/abs/1803.08100](https://arxiv.org/abs/1803.08100)

##### PDF
[https://arxiv.org/pdf/1803.08100](https://arxiv.org/pdf/1803.08100)

