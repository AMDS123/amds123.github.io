---
layout: post
title: "Learning Actionable Representations from Visual Observations"
date: 2018-08-02 17:24:54
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning Embedding Optimization
author: Debidatta Dwibedi, Jonathan Tompson, Corey Lynch, Pierre Sermanet
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we explore a new approach for robots to teach themselves about the world simply by observing it. In particular we investigate the effectiveness of learning task-agnostic representations for continuous control tasks. We extend Time-Contrastive Networks (TCN) that learn from visual observations by embedding multiple frames jointly in the embedding space as opposed to a single frame. We show that by doing so, we are now able to encode both position and velocity attributes significantly more accurately. We test the usefulness of this self-supervised approach in a reinforcement learning setting. We show that the representations learned by agents observing themselves take random actions, or other agents perform tasks successfully, can enable the learning of continuous control policies using algorithms like Proximal Policy Optimization (PPO) using only the learned embeddings as input. We also demonstrate significant improvements on the real-world Pouring dataset with a relative error reduction of 39.4% for motion attributes and 11.1% for static attributes compared to the single-frame baseline. Video results are available at https://sites.google.com/view/actionablerepresentations .

##### Abstract (translated by Google)
在这项工作中，我们探索了一种机器人通过观察它来自我教导世界的新方法。特别是，我们研究了学习任务不可知表示对连续控制任务的有效性。我们扩展了时间 - 对比网络（TCN），它通过在嵌入空间中共同嵌入多个帧而不是单个帧来从视觉观察中学习。我们通过这样做表明，我们现在能够更准确地对位置和速度属性进行编码。我们在强化学习环境中测试这种自我监督方法的有用性。我们表明，代理观察自己采取的表示采取随机行动，或者其他代理成功执行任务，可以使用仅使用学习嵌入作为输入的近端策略优化（PPO）等算法来学习连续控制策略。我们还展示了对真实世界Pouring数据集的重大改进，与单帧基线相比，运动属性的相对误差降低了39.4％，静态属性的相对误差降低了11.1％。视频结果可在https://sites.google.com/view/actionablerepresentations上找到。

##### URL
[http://arxiv.org/abs/1808.00928](http://arxiv.org/abs/1808.00928)

##### PDF
[http://arxiv.org/pdf/1808.00928](http://arxiv.org/pdf/1808.00928)

