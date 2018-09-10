---
layout: post
title: "Improving On-policy Learning with Statistical Reward Accumulation"
date: 2018-09-07 10:10:12
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning
author: Yubin Deng, Ke Yu, Dahua Lin, Xiaoou Tang, Chen Change Loy
mathjax: true
---

* content
{:toc}

##### Abstract
Deep reinforcement learning has obtained significant breakthroughs in recent years. Most methods in deep-RL achieve good results via the maximization of the reward signal provided by the environment, typically in the form of discounted cumulative returns. Such reward signals represent the immediate feedback of a particular action performed by an agent. However, tasks with sparse reward signals are still challenging to on-policy methods. In this paper, we introduce an effective characterization of past reward statistics (which can be seen as long-term feedback signals) to supplement this immediate reward feedback. In particular, value functions are learned with multi-critics supervision, enabling complex value functions to be more easily approximated in on-policy learning, even when the reward signals are sparse. We also introduce a novel exploration mechanism called "hot-wiring" that can give a boost to seemingly trapped agents. We demonstrate the effectiveness of our advantage actor multi-critic (A2MC) method across the discrete domains in Atari games as well as continuous domains in the MuJoCo environments. A video demo is provided at https://youtu.be/zBmpf3Yz8tc.

##### Abstract (translated by Google)
深层强化学习近年来取得了重大突破。深度RL中的大多数方法通过环境提供的奖励信号的最大化来实现良好结果，通常以折扣累积回报的形式。这种奖励信号代表由代理执行的特定动作的即时反馈。然而，具有稀疏奖励信号的任务仍然对政策方法具有挑战性。在本文中，我们介绍了过去奖励统计数据的有效表征（可以看作是长期反馈信号），以补充这种即时的奖励反馈。特别是，价值函数是通过多评论家监督来学习的，即使在奖励信号稀疏的情况下，也能够在政策学习中更容易地近似复杂的价值函数。我们还引入了一种名为“热线”的新型探测机制，可以增强看似被困的特工。我们展示了我们的优势演员多评论（A2MC）方法在Atari游戏中的离散域以及MuJoCo环境中的连续域中的有效性。视频演示在https://youtu.be/zBmpf3Yz8tc上提供。

##### URL
[http://arxiv.org/abs/1809.02387](http://arxiv.org/abs/1809.02387)

##### PDF
[http://arxiv.org/pdf/1809.02387](http://arxiv.org/pdf/1809.02387)

