---
layout: post
title: "Learning a Structured Neural Network Policy for a Hopping Task"
date: 2018-08-06 14:31:13
categories: arXiv_RO
tags: arXiv_RO
author: Julian Viereck, Jules Kozolinsky, Alexander Herzog, Ludovic Righetti
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we present a method for learning a reactive policy for a simple dynamic locomotion task involving hard impact and switching contacts where we assume the contact location and contact timing to be unknown. To learn such a policy, we use optimal control to optimize a local controller for a fixed environment and contacts. We learn the contact-rich dynamics for our underactuated systems along these trajectories in a sample efficient manner. We use the optimized policies to learn the reactive policy in form of a neural network. Using a new neural network architecture, we are able to preserve more information from the local policy and make its output interpretable in the sense that its output in terms of desired trajectories, feedforward commands and gains can be interpreted. Extensive simulations demonstrate the robustness of the approach to changing environments, outperforming a model-free gradient policy based methods on the same tasks in simulation. Finally, we show that the learned policy can be robustly transferred on a real robot.

##### Abstract (translated by Google)
在这项工作中，我们提出了一种学习反应策略的方法，该策略用于涉及硬碰撞和切换接触的简单动态运动任务，其中我们假设接触位置和接触时间是未知的。为了学习这样的策略，我们使用最优控制来优化固定环境和联系人的本地控制器。我们以样本有效的方式了解这些轨迹中欠驱动系统的接触丰富动态。我们使用优化策略以神经网络的形式学习反应策略。使用新的神经网络架构，我们能够从本地策略中保留更多信息，并使其输出可解释，即可以解释其在所需轨迹，前馈命令和增益方面的输出。大量仿真证明了该方法对于改变环境的稳健性，在模拟中对同一任务的性能优于无模型梯度策略。最后，我们表明，学习的策略可以在真实的机器人上强有力地转移。

##### URL
[http://arxiv.org/abs/1710.00022](http://arxiv.org/abs/1710.00022)

##### PDF
[http://arxiv.org/pdf/1710.00022](http://arxiv.org/pdf/1710.00022)

