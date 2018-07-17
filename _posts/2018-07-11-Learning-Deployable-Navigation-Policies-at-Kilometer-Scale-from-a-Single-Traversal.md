---
layout: post
title: "Learning Deployable Navigation Policies at Kilometer Scale from a Single Traversal"
date: 2018-07-11 11:05:12
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning Embedding
author: Jake Bruce, Niko S&#xfc;nderhauf, Piotr Mirowski, Raia Hadsell, Michael Milford
mathjax: true
---

* content
{:toc}

##### Abstract
Model-free reinforcement learning has recently been shown to be effective at learning navigation policies from complex image input. However, these algorithms tend to require large amounts of interaction with the environment, which can be prohibitively costly to obtain on robots in the real world. We present an approach for efficiently learning goal-directed navigation policies on a mobile robot, from only a single coverage traversal of recorded data. The navigation agent learns an effective policy over a diverse action space in a large heterogeneous environment consisting of more than 2km of travel, through buildings and outdoor regions that collectively exhibit large variations in visual appearance, self-similarity, and connectivity. We compare pretrained visual encoders that enable precomputation of visual embeddings to achieve a throughput of tens of thousands of transitions per second at training time on a commodity desktop computer, allowing agents to learn from millions of trajectories of experience in a matter of hours. We propose multiple forms of computationally efficient stochastic augmentation to enable the learned policy to generalise beyond these precomputed embeddings, and demonstrate successful deployment of the learned policy on the real robot without fine tuning, despite environmental appearance differences at test time. The dataset and code required to reproduce these results and apply the technique to other datasets and robots is made publicly available at rl-navigation.github.io/deployable.

##### Abstract (translated by Google)
最近证明，无模型强化学习在学习复杂图像输入的导航策略方面是有效的。然而，这些算法往往需要与环境进行大量的交互，这在现实世界中的机器人上获得的成本过高。我们提出了一种方法，用于在移动机器人上有效地学习目标导向策略，仅从记录数据的单个覆盖遍历开始。导航代理通过建筑物和室外区域共同展现出视觉外观，自相似性和连通性的巨大变化，在超过2km的旅行的大型异构环境中学习多种行动空间的有效策略。我们比较了预先训练的视觉编码器，它们可以实现视觉嵌入的预计算，在商用台式计算机上实现每秒数万次转换的吞吐量，使代理商能够在数小时内从数百万的经验轨迹中学习。我们提出了多种形式的计算有效的随机扩充，以使学习的策略能够超越这些预先计算的嵌入，并演示在没有微调的情况下在真实机器人上成功部署学习策略，尽管在测试时环境外观差异。重现这些结果并将该技术应用于其他数据集和机器人所需的数据集和代码可在rl-navigation.github.io/deployable上公开获取。

##### URL
[http://arxiv.org/abs/1807.05211](http://arxiv.org/abs/1807.05211)

##### PDF
[http://arxiv.org/pdf/1807.05211](http://arxiv.org/pdf/1807.05211)

