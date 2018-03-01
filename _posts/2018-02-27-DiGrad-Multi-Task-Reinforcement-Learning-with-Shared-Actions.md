---
layout: post
title: "DiGrad: Multi-Task Reinforcement Learning with Shared Actions"
date: 2018-02-27 10:26:08
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Parijat Dewangan, S Phaniteja, K Madhava Krishna, Abhishek Sarkar, Balaraman Ravindran
mathjax: true
---

* content
{:toc}

##### Abstract
Most reinforcement learning algorithms are inefficient for learning multiple tasks in complex robotic systems, where different tasks share a set of actions. In such environments a compound policy may be learnt with shared neural network parameters, which performs multiple tasks concurrently. However such compound policy may get biased towards a task or the gradients from different tasks negate each other, making the learning unstable and sometimes less data efficient. In this paper, we propose a new approach for simultaneous training of multiple tasks sharing a set of common actions in continuous action spaces, which we call as DiGrad (Differential Policy Gradient). The proposed framework is based on differential policy gradients and can accommodate multi-task learning in a single actor-critic network. We also propose a simple heuristic in the differential policy gradient update to further improve the learning. The proposed architecture was tested on 8 link planar manipulator and 27 degrees of freedom(DoF) Humanoid for learning multi-goal reachability tasks for 3 and 2 end effectors respectively. We show that our approach supports efficient multi-task learning in complex robotic systems, outperforming related methods in continuous action spaces.

##### Abstract (translated by Google)
大多数强化学习算法对于学习复杂机器人系统中的多个任务而言效率低下，其中不同任务共享一组操作。在这样的环境中，可以使用共享神经网络参数来学习复合策略，其同时执行多个任务。然而，这种复合策略可能会偏向某项任务，或者来自不同任务的梯度会相互抵消，从而导致学习不稳定，有时数据效率较低。在本文中，我们提出了一种同时训练多个任务的新方法，它们在连续动作空间中共享一组共同动作，我们称之为DiGrad（差分策略梯度）。所提出的框架基于不同的策略梯度，并且可以适应单个评论者网络中的多任务学习。我们还提出了一种简单的启发式算法，用于进一步改进学习。所提出的架构在8个链接平面操纵器和27个自由度（DoF）Humanoid上进行测试，以分别为3个和2个末端执行器学习多目标可达性任务。我们表明，我们的方法支持复杂机器人系统中的高效多任务学习，优于连续动作空间中的相关方法。

##### URL
[http://arxiv.org/abs/1802.10463](http://arxiv.org/abs/1802.10463)

##### PDF
[http://arxiv.org/pdf/1802.10463](http://arxiv.org/pdf/1802.10463)

