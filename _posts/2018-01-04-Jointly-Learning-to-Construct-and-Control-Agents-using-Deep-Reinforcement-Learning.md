---
layout: post
title: "Jointly Learning to Construct and Control Agents using Deep Reinforcement Learning"
date: 2018-01-04 16:39:08
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning
author: Charles Schaff, David Yunis, Ayan Chakrabarti, Matthew R. Walter
mathjax: true
---

* content
{:toc}

##### Abstract
The physical design of a robot and the policy that controls its motion are inherently coupled. However, existing approaches largely ignore this coupling, instead choosing to alternate between separate design and control phases, which requires expert intuition throughout and risks convergence to suboptimal designs. In this work, we propose a method that jointly optimizes over the physical design of a robot and the corresponding control policy in a model-free fashion, without any need for expert supervision. Given an arbitrary robot morphology, our method maintains a distribution over the design parameters and uses reinforcement learning to train a neural network controller. Throughout training, we refine the robot distribution to maximize the expected reward. This results in an assignment to the robot parameters and neural network policy that are jointly optimal. We evaluate our approach in the context of legged locomotion, and demonstrate that it discovers novel robot designs and walking gaits for several different morphologies, achieving performance comparable to or better than that of hand-crafted designs.

##### Abstract (translated by Google)
机器人的物理设计和控制其运动的策略本质上是耦合的。然而，现有的方法很大程度上忽略了这种耦合，而是选择在独立的设计阶段和控制阶段之间进行交替，这需要整个专家的直觉，并且将风险收敛到次优设计。在这项工作中，我们提出了一种方法，在没有任何专家监督的情况下，以模型方式联合优化机器人的物理设计和相应的控制策略。给定一个任意的机器人形态，我们的方法在设计参数上保持分布，并使用强化学习来训练一个神经网络控制器。在整个培训过程中，我们改进机器人分配以最大化期望的奖励。这导致分配给机器人参数和神经网络策略是联合最优的。我们评估我们的方法在腿部运动的情况下，并表明它发现了新的机器人设计和几种不同形态的步态步态，实现了与手工设计相媲美或更好的性能。

##### URL
[http://arxiv.org/abs/1801.01432](http://arxiv.org/abs/1801.01432)

##### PDF
[http://arxiv.org/pdf/1801.01432](http://arxiv.org/pdf/1801.01432)

