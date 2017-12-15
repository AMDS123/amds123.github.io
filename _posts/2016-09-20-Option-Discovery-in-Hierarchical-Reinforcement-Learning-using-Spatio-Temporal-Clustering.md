---
layout: post
title: "Option Discovery in Hierarchical Reinforcement Learning using Spatio-Temporal Clustering"
date: 2016-09-20 19:14:20
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning Prediction
author: Aravind S. Lakshminarayanan, Ramnandan Krishnamurthy, Peeyush Kumar, Balaraman Ravindran
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces an automated skill acquisition framework in reinforcement learning which involves identifying a hierarchical description of the given task in terms of abstract states and extended actions between abstract states. Identifying such structures present in the task provides ways to simplify and speed up reinforcement learning algorithms. These structures also help to generalize such algorithms over multiple tasks without relearning policies from scratch. We use ideas from dynamical systems to find metastable regions in the state space and associate them with abstract states. The spectral clustering algorithm PCCA+ is used to identify suitable abstractions aligned to the underlying structure. Skills are defined in terms of the sequence of actions that lead to transitions between such abstract states. The connectivity information from PCCA+ is used to generate these skills or options. These skills are independent of the learning task and can be efficiently reused across a variety of tasks defined over the same model. This approach works well even without the exact model of the environment by using sample trajectories to construct an approximate estimate. We also present our approach to scaling the skill acquisition framework to complex tasks with large state spaces for which we perform state aggregation using the representation learned from an action conditional video prediction network and use the skill acquisition framework on the aggregated state space.

##### Abstract (translated by Google)
本文介绍了一个强化学习中的自动技能获取框架，其中包括根据抽象状态和抽象状态之间的扩展行为来识别给定任务的分层描述。识别任务中存在的这种结构提供了简化和加速强化学习算法的方法。这些结构还有助于将这些算法概括为多个任务，而无需从头开始重新学习策略。我们使用动态系统的思想来寻找状态空间中的亚稳态区域，并将它们与抽象状态联系起来。谱聚类算法PCCA +被用来识别与底层结构对齐的合适的抽象。技能是根据导致这种抽象状态之间转换的行为顺序来定义的。来自PCCA +的连接信息被用来产生这些技能或选项。这些技能独立于学习任务，可以在同一模型中定义的各种任务中高效地重复使用。即使没有环境的确切模型，通过使用样本轨迹来构建近似估计，这种方法也能很好地工作。我们还提出了将技能获取框架扩展到具有大状态空间的复杂任务的方法，其中我们使用从动作条件视频预测网络学习的表示来执行状态聚合，并且在聚合状态空间上使用技能获取框架。

##### URL
[https://arxiv.org/abs/1605.05359](https://arxiv.org/abs/1605.05359)

##### PDF
[https://arxiv.org/pdf/1605.05359](https://arxiv.org/pdf/1605.05359)

