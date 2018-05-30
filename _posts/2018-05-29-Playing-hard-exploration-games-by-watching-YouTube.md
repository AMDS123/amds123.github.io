---
layout: post
title: "Playing hard exploration games by watching YouTube"
date: 2018-05-29 17:19:36
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning
author: Yusuf Aytar, Tobias Pfaff, David Budden, Tom Le Paine, Ziyu Wang, Nando de Freitas
mathjax: true
---

* content
{:toc}

##### Abstract
Deep reinforcement learning methods traditionally struggle with tasks where environment rewards are particularly sparse. One successful method of guiding exploration in these domains is to imitate trajectories provided by a human demonstrator. However, these demonstrations are typically collected under artificial conditions, i.e. with access to the agent's exact environment setup and the demonstrator's action and reward trajectories. Here we propose a two-stage method that overcomes these limitations by relying on noisy, unaligned footage without access to such data. First, we learn to map unaligned videos from multiple sources to a common representation using self-supervised objectives constructed over both time and modality (i.e. vision and sound). Second, we embed a single YouTube video in this representation to construct a reward function that encourages an agent to imitate human gameplay. This method of one-shot imitation allows our agent to convincingly exceed human-level performance on the infamously hard exploration games Montezuma's Revenge, Pitfall! and Private Eye for the first time, even if the agent is not presented with any environment rewards.

##### Abstract (translated by Google)
传统上，深度强化学习方法与环境奖励特别稀疏的任务相抗衡。指导这些领域探索的成功方法是模仿人类示威者提供的轨迹。然而，这些演示通常是在人为条件下收集的，即可以访问代理商的确切环境设置和演示者的行动和奖励轨迹。在这里，我们提出了一种两阶段方法，通过依靠嘈杂的，未对齐的素材而无需访问这些数据来克服这些限制。首先，我们学习使用在时间和模态（即视觉和声音）上构建的自监督目标将来自多个来源的未对齐视频映射到共同表示。其次，我们在此表示中嵌入一个YouTube视频，以构建奖励功能，鼓励座席模仿人类的游戏玩法。这种一次模仿的方法允许我们的代理人在令人难以置信的艰难探索游戏蒙特祖玛的复仇，陷阱中令人信服地超越人类表现！和私人眼睛，即使代理人没有获得任何环境奖励。

##### URL
[http://arxiv.org/abs/1805.11592](http://arxiv.org/abs/1805.11592)

##### PDF
[http://arxiv.org/pdf/1805.11592](http://arxiv.org/pdf/1805.11592)

