---
layout: post
title: "Shared Autonomy via Deep Reinforcement Learning"
date: 2018-02-06 00:45:12
categories: arXiv_RO
tags: arXiv_RO Knowledge Reinforcement_Learning
author: Siddharth Reddy, Sergey Levine, Anca Dragan
mathjax: true
---

* content
{:toc}

##### Abstract
In shared autonomy, user input is combined with semi-autonomous control to achieve a common goal. The goal is often unknown ex-ante, so prior work enables agents to infer the goal from user input and assist with the task. Such methods tend to assume some combination of knowledge of the dynamics of the environment, the user's policy given their goal, and the set of possible goals the user might target, which limits their application to real-world scenarios. We propose a deep reinforcement learning framework for model-free shared autonomy that lifts these assumptions. We use human-in-the-loop reinforcement learning with neural network function approximation to learn an end-to-end mapping from environmental observation and user input to agent action, with task reward as the only form of supervision. Controlled studies with users (n = 16) and synthetic pilots playing a video game and flying a real quadrotor demonstrate the ability of our algorithm to assist users with real-time control tasks in which the agent cannot directly access the user's private information through observations, but receives a reward signal and user input that both depend on the user's intent. The agent learns to assist the user without access to this private information, implicitly inferring it from the user's input. This allows the assisted user to complete the task more effectively than the user or an autonomous agent could on their own. This paper is a proof of concept that illustrates the potential for deep reinforcement learning to enable flexible and practical assistive systems.

##### Abstract (translated by Google)
在共享自治中，用户输入与半自主控制相结合以实现共同目标。目标往往是事先未知的，所以之前的工作使代理人能够从用户输入中推断目标并协助完成任务。这样的方法倾向于假定环境动态的知识，给定目标的用户策略以及用户可能的目标集合的一些组合，这限制了它们在真实场景中的应用。我们提出了一个深化的强化学习框架模型免费共享自治提升这些假设。我们使用神经网络函数逼近的人在环强化学习来学习从环境观察和用户输入到代理行为的端到端映射，任务奖励是唯一的监督形式。用户（n = 16）和合成飞行员玩视频游戏和飞行真正的四旋翼飞行器的受控研究证明了我们的算法帮助用户进行实时控制任务的能力，其中代理人不能通过观察直接访问用户的私人信息，但是接收依赖于用户意图的奖励信号和用户输入。代理学会帮助用户不访问这些私人信息，从用户的输入中隐含地推断它。这允许辅助用户比用户或自主代理能够更有效地完成任务。本文是一个概念证明，说明深入强化学习的潜力，以实现灵活和实用的辅助系统。

##### URL
[http://arxiv.org/abs/1802.01744](http://arxiv.org/abs/1802.01744)

##### PDF
[http://arxiv.org/pdf/1802.01744](http://arxiv.org/pdf/1802.01744)

