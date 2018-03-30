---
layout: post
title: "Autonomous Ramp Merge Maneuver Based on Reinforcement Learning with Continuous Action Space"
date: 2018-03-25 05:10:10
categories: arXiv_AI
tags: arXiv_AI Adversarial Reinforcement_Learning
author: Pin Wang, Ching-Yao Chan
mathjax: true
---

* content
{:toc}

##### Abstract
Ramp merging is a critical maneuver for road safety and traffic efficiency. Most of the current automated driving systems developed by multiple automobile manufacturers and suppliers are typically limited to restricted access freeways only. Extending the automated mode to ramp merging zones presents substantial challenges. One is that the automated vehicle needs to incorporate a future objective (e.g. a successful and smooth merge) and optimize a long-term reward that is impacted by subsequent actions when executing the current action. Furthermore, the merging process involves interaction between the merging vehicle and its surrounding vehicles whose behavior may be cooperative or adversarial, leading to distinct merging countermeasures that are crucial to successfully complete the merge. In place of the conventional rule-based approaches, we propose to apply reinforcement learning algorithm on the automated vehicle agent to find an optimal driving policy by maximizing the long-term reward in an interactive driving environment. Most importantly, in contrast to most reinforcement learning applications in which the action space is resolved as discrete, our approach treats the action space as well as the state space as continuous without incurring additional computational costs. Our unique contribution is the design of the Q-function approximation whose format is structured as a quadratic function, by which simple but effective neural networks are used to estimate its coefficients. The results obtained through the implementation of our training platform demonstrate that the vehicle agent is able to learn a safe, smooth and timely merging policy, indicating the effectiveness and practicality of our approach.

##### Abstract (translated by Google)
斜坡合并是道路安全和交通效率的关键操作。由多个汽车制造商和供应商开发的大多数目前的自动驾驶系统通常仅限于限制通道高速公路。将自动化模式扩展到斜坡合并区带来了重大挑战。一个是自动车辆需要结合未来目标（例如成功和平稳的合并）并且优化在执行当前动作时受随后动作影响的长期奖励。此外，合并过程涉及合并车辆与其行为可能是合作或对抗的周边车辆之间的相互作用，从而导致对成功完成合并至关重要的独特合并对策。为取代传统的基于规则的方法，我们建议对自动车辆代理应用强化学习算法，以通过在交互式驾驶环境中最大化长期奖励来找到最佳驾驶策略。最重要的是，与其中动作空间被解析为离散的大多数强化学习应用相反，我们的方法将动作空间以及状态空间视为连续的，而不会产生额外的计算成本。我们独特的贡献是Q函数逼近的设计，其格式被构造为二次函数，其中使用简单但有效的神经网络来估计其系数。通过实施我们的培训平台获得的结果表明，车辆代理能够学习安全，平稳和及时的合并政策，显示我们方法的有效性和实用性。

##### URL
[https://arxiv.org/abs/1803.09203](https://arxiv.org/abs/1803.09203)

##### PDF
[https://arxiv.org/pdf/1803.09203](https://arxiv.org/pdf/1803.09203)

