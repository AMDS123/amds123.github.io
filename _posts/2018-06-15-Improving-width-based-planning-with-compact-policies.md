---
layout: post
title: "Improving width-based planning with compact policies"
date: 2018-06-15 10:41:23
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning
author: Miquel Junyent, Anders Jonsson, Vicen&#xe7; G&#xf3;mez
mathjax: true
---

* content
{:toc}

##### Abstract
Optimal action selection in decision problems characterized by sparse, delayed rewards is still an open challenge. For these problems, current deep reinforcement learning methods require enormous amounts of data to learn controllers that reach human-level performance. In this work, we propose a method that interleaves planning and learning to address this issue. The planning step hinges on the Iterated-Width (IW) planner, a state of the art planner that makes explicit use of the state representation to perform structured exploration. IW is able to scale up to problems independently of the size of the state space. From the state-actions visited by IW, the learning step estimates a compact policy, which in turn is used to guide the planning step. The type of exploration used by our method is radically different than the standard random exploration used in RL. We evaluate our method in simple problems where we show it to have superior performance than the state-of-the-art reinforcement learning algorithms A2C and Alpha Zero. Finally, we present preliminary results in a subset of the Atari games suite.

##### Abstract (translated by Google)
以稀疏，延迟奖励为特征的决策问题中的最优行动选择仍然是一个公开挑战。针对这些问题，目前深入的强化学习方法需要大量的数据来学习控制器达到人类级别的性能。在这项工作中，我们提出了一种交错计划和学习来解决这个问题的方法。规划步骤取决于迭代宽度（IW）规划器，这是一种先进的规划器，它明确使用状态表示来执行结构化的勘探。 IW可以扩展到独立于状态空间大小的问题。从IW访问的国家行为中，学习步骤估计出一个紧凑的政策，这反过来又被用来指导计划步骤。我们的方法使用的勘探类型与RL中使用的标准随机勘探完全不同。我们在简单问题中评估我们的方法，我们证明它的性能优于最先进的强化学习算法A2C和Alpha Zero。最后，我们在Atari游戏套件的一个子集中提供初步结果。

##### URL
[http://arxiv.org/abs/1806.05898](http://arxiv.org/abs/1806.05898)

##### PDF
[http://arxiv.org/pdf/1806.05898](http://arxiv.org/pdf/1806.05898)

