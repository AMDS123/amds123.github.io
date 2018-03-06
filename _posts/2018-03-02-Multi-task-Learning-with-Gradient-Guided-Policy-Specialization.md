---
layout: post
title: "Multi-task Learning with Gradient Guided Policy Specialization"
date: 2018-03-02 22:23:00
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Wenhao Yu, C. Karen Liu, Greg Turk
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method for efficient learning of control policies for multiple related robotic motor skills. Our approach consists of two stages, joint training and specialization training. During the joint training stage, a neural network policy is trained with minimal information to disambiguate the motor skills. This forces the policy to learn a common representation of the different tasks. Then, during the specialization training stage we selectively split the weights of the policy based on a per-weight metric that measures the disagreement among the multiple tasks. By splitting part of the control policy, it can be further trained to specialize to each task. To update the control policy during learning, we use Trust Region Policy Optimization with Generalized Advantage Function (TRPOGAE). We propose a modification to the gradient update stage of TRPO to better accommodate multi-task learning scenarios. We evaluate our approach on three continuous motor skill learning problems in simulation: 1) a locomotion task where three single legged robots with considerable difference in shape and size are trained to hop forward, 2) a manipulation task where three robot manipulators with different sizes and joint types are trained to reach different locations in 3D space, and 3) locomotion of a two-legged robot, whose range of motion of one leg is constrained in different ways. We compare our training method to three baselines. The first baseline uses only joint training for the policy, the second trains independent policies for each task, and the last randomly selects weights to split. We show that our approach learns more efficiently than each of the baseline methods.

##### Abstract (translated by Google)
我们提出了一种有效学习多种相关机器人运动技能的控制策略的方法。我们的方法包括两个阶段，即联合培训和专业化培训。在联合训练阶段，神经网络策略以最少的信息进行训练，以消除运动技能的歧义。这迫使政策学习不同任务的共同表示。然后，在专业化培训阶段，我们根据衡量多个任务之间不一致的每个权重指标有选择地分割策略的权重。通过分解部分控制策略，可以进一步培训专门针对每项任务。为了在学习期间更新控制策略，我们使用带广义优势函数的信任域策略优化（TRPOGAE）。我们建议修改TRPO的渐变更新阶段，以更好地适应多任务学习场景。我们在模拟中评估我们的三种连续运动技能学习问题的方法：1）运动任务，其中三个形状和尺寸差异很大的单腿机器人被训练向前跳，2）一个操纵任务，其中三个机器人机器人具有不同的尺寸和关节类型被训练到三维空间中的不同位置，以及3）双腿机器人的运动，其一条腿的运动范围受到不同方式的限制。我们将我们的训练方法与三条基线进行比较。第一条基线只使用联合培训进行策略，第二条基线为每项任务培训独立策略，最后随机选择权重进行拆分。我们表明，我们的方法比每种基准方法更有效地学习。

##### URL
[http://arxiv.org/abs/1709.07979](http://arxiv.org/abs/1709.07979)

##### PDF
[http://arxiv.org/pdf/1709.07979](http://arxiv.org/pdf/1709.07979)

