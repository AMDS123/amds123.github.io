---
layout: post
title: "End-to-End Training of Deep Visuomotor Policies"
date: 2016-04-19 01:33:13
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning CNN
author: Sergey Levine, Chelsea Finn, Trevor Darrell, Pieter Abbeel
mathjax: true
---

* content
{:toc}

##### Abstract
Policy search methods can allow robots to learn control policies for a wide range of tasks, but practical applications of policy search often require hand-engineered components for perception, state estimation, and low-level control. In this paper, we aim to answer the following question: does training the perception and control systems jointly end-to-end provide better performance than training each component separately? To this end, we develop a method that can be used to learn policies that map raw image observations directly to torques at the robot's motors. The policies are represented by deep convolutional neural networks (CNNs) with 92,000 parameters, and are trained using a partially observed guided policy search method, which transforms policy search into supervised learning, with supervision provided by a simple trajectory-centric reinforcement learning method. We evaluate our method on a range of real-world manipulation tasks that require close coordination between vision and control, such as screwing a cap onto a bottle, and present simulated comparisons to a range of prior policy search methods.

##### Abstract (translated by Google)
策略搜索方法可以使机器人学习广泛的任务的控制策略，但政策搜索的实际应用往往需要手工组件来进行感知，状态估计和低级控制。在本文中，我们的目标是回答以下问题：端到端联合训练感知和控制系统是否比单独训练每个组件更好地提供性能？为此，我们开发了一种方法，可以用来学习将原始图像观察直接映射到机器人电机的转矩的策略。这些策略由92,000个参数的深度卷积神经网络（CNNs）表示，并且使用部分观察的引导策略搜索方法进行训练，该策略搜索方法将策略搜索转换为监督学习，通过简单的以轨迹为中心的强化学习方法提供监督。我们对一系列需要视觉和控制之间密切协调的真实世界的操作任务进行了评估，例如将瓶盖拧到瓶子上，并将模拟比较提供给一系列先前的策略搜索方法。

##### URL
[https://arxiv.org/abs/1504.00702](https://arxiv.org/abs/1504.00702)

##### PDF
[https://arxiv.org/pdf/1504.00702](https://arxiv.org/pdf/1504.00702)

