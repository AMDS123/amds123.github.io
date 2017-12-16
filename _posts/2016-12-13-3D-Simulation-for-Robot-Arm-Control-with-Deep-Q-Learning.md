---
layout: post
title: "3D Simulation for Robot Arm Control with Deep Q-Learning"
date: 2016-12-13 16:09:17
categories: arXiv_CV
tags: arXiv_CV Knowledge Reinforcement_Learning
author: Stephen James, Edward Johns
mathjax: true
---

* content
{:toc}

##### Abstract
Recent trends in robot arm control have seen a shift towards end-to-end solutions, using deep reinforcement learning to learn a controller directly from raw sensor data, rather than relying on a hand-crafted, modular pipeline. However, the high dimensionality of the state space often means that it is impractical to generate sufficient training data with real-world experiments. As an alternative solution, we propose to learn a robot controller in simulation, with the potential of then transferring this to a real robot. Building upon the recent success of deep Q-networks, we present an approach which uses 3D simulations to train a 7-DOF robotic arm in a control task without any prior knowledge. The controller accepts images of the environment as its only input, and outputs motor actions for the task of locating and grasping a cube, over a range of initial configurations. To encourage efficient learning, a structured reward function is designed with intermediate rewards. We also present preliminary results in direct transfer of policies over to a real robot, without any further training.

##### Abstract (translated by Google)
最近机器人手臂控制的趋势已经转向端到端的解决方案，使用深入的强化学习直接从原始传感器数据中学习控制器，而不是依靠手工制作的模块化管线。然而，状态空间的高维通常意味着用真实世界的实验产生足够的训练数据是不切实际的。作为一种替代解决方案，我们建议在模拟中学习机器人控制器，然后将其转换为真正的机器人。基于深度Q网络的最近成功，我们提出了一种方法，其使用3D模拟在控制任务中训练一个7自由度机器人手臂而不需要任何预先知识。控制器接受环境的图像作为其唯一的输入，并在一系列初始配置中输出用于定位和抓取立方体的任务的电机动作。为了鼓励有效的学习，结构化的奖励功能被设计为中间奖励。我们还提供了初步的结果，直接转交给一个真正的机器人，没有任何进一步的培训。

##### URL
[https://arxiv.org/abs/1609.03759](https://arxiv.org/abs/1609.03759)

##### PDF
[https://arxiv.org/pdf/1609.03759](https://arxiv.org/pdf/1609.03759)

