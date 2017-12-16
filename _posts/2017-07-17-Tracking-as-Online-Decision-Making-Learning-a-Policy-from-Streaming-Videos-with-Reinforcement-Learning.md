---
layout: post
title: "Tracking as Online Decision-Making: Learning a Policy from Streaming Videos with Reinforcement Learning"
date: 2017-07-17 03:38:35
categories: arXiv_CV
tags: arXiv_CV Sparse Tracking Reinforcement_Learning
author: James Steven Supancic III, Deva Ramanan
mathjax: true
---

* content
{:toc}

##### Abstract
We formulate tracking as an online decision-making process, where a tracking agent must follow an object despite ambiguous image frames and a limited computational budget. Crucially, the agent must decide where to look in the upcoming frames, when to reinitialize because it believes the target has been lost, and when to update its appearance model for the tracked object. Such decisions are typically made heuristically. Instead, we propose to learn an optimal decision-making policy by formulating tracking as a partially observable decision-making process (POMDP). We learn policies with deep reinforcement learning algorithms that need supervision (a reward signal) only when the track has gone awry. We demonstrate that sparse rewards allow us to quickly train on massive datasets, several orders of magnitude more than past work. Interestingly, by treating the data source of Internet videos as unlimited streams, we both learn and evaluate our trackers in a single, unified computational stream.

##### Abstract (translated by Google)
我们将跟踪制定为一个在线决策过程，跟踪代理必须跟踪一个对象，尽管模糊的图像帧和有限的计算预算。至关重要的是，代理必须决定在即将到来的帧中的何处查看，何时重新初始化，因为它认为目标已经丢失，以及何时更新跟踪对象的外观模型。这样的决定通常是启发式的。相反，我们建议通过将追踪作为部分可观察的决策过程（POMDP）来学习最优的决策策略。我们学习的策略只有在轨道出错的时候才需要监督（奖励信号）。我们证明，稀疏奖励使我们能够快速训练海量数据集，比以往的工作量要多出几个数量级。有趣的是，通过将互联网视频的数据源视为无限流，我们都可以在统一的计算流中学习和评估我们的追踪器。

##### URL
[https://arxiv.org/abs/1707.04991](https://arxiv.org/abs/1707.04991)

##### PDF
[https://arxiv.org/pdf/1707.04991](https://arxiv.org/pdf/1707.04991)

