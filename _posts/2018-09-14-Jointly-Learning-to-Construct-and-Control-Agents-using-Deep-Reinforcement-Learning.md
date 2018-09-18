---
layout: post
title: "Jointly Learning to Construct and Control Agents using Deep Reinforcement Learning"
date: 2018-09-14 19:27:56
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning Optimization
author: Charles Schaff, David Yunis, Ayan Chakrabarti, Matthew R. Walter
mathjax: true
---

* content
{:toc}

##### Abstract
The physical design of a robot and the policy that controls its motion are inherently coupled, and should be determined according to the task and environment. In an increasing number of applications, data-driven and learning-based approaches, such as deep reinforcement learning, have proven effective at designing control policies. For most tasks, the only way to evaluate a physical design with respect to such control policies is empirical--i.e., by picking a design and training a control policy for it. Since training these policies is time-consuming, it is computationally infeasible to train separate policies for all possible designs as a means to identify the best one. In this work, we address this limitation by introducing a method that performs simultaneous joint optimization of the physical design and control network. Our approach maintains a distribution over designs and uses reinforcement learning to optimize a control policy to maximize expected reward over the design distribution. We give the controller access to design parameters to allow it to tailor its policy to each design in the distribution. Throughout training, we shift the distribution towards higher-performing designs, eventually converging to a design and control policy that are jointly optimal. We evaluate our approach in the context of legged locomotion, and demonstrate that it discovers novel designs and walking gaits, outperforming baselines in both performance and efficiency.

##### Abstract (translated by Google)
机器人的物理设计和控制其运动的策略本质上是耦合的，应根据任务和环境来确定。在越来越多的应用中，数据驱动和基于学习的方法，例如深度强化学习，已被证明在设计控制策略方面是有效的。对于大多数任务而言，评估与这种控制策略相关的物理设计的唯一方法是经验性的 - 即，通过选择设计并为其训练控制策略。由于培训这些政策非常耗时，因此在计算上不可能为所有可能的设计培训单独的政策，以此作为识别最佳设计的手段。在这项工作中，我们通过引入一种同时联合优化物理设计和控制网络的方法来解决这一局限。我们的方法保持对设计的分布，并使用强化学习来优化控制策略，以最大化设计分布的预期回报。我们让控制器访问设计参数，以允许它根据分布中的每个设计定制其策略。在整个培训过程中，我们将分布转向更高性能的设计，最终融合到共同最优的设计和控制策略中。我们在腿部运动的背景下评估我们的方法，并证明它发现了新颖的设计和步态步态，在性能和效率方面都超越了基线。

##### URL
[http://arxiv.org/abs/1801.01432](http://arxiv.org/abs/1801.01432)

##### PDF
[http://arxiv.org/pdf/1801.01432](http://arxiv.org/pdf/1801.01432)

