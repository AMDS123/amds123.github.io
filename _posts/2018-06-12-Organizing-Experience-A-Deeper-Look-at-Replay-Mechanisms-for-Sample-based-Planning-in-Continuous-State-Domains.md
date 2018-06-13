---
layout: post
title: "Organizing Experience: A Deeper Look at Replay Mechanisms for Sample-based Planning in Continuous State Domains"
date: 2018-06-12 16:07:31
categories: arXiv_AI
tags: arXiv_AI GAN
author: Yangchen Pan, Muhammad Zaheer, Adam White, Andrew Patterson, Martha White
mathjax: true
---

* content
{:toc}

##### Abstract
Model-based strategies for control are critical to obtain sample efficient learning. Dyna is a planning paradigm that naturally interleaves learning and planning, by simulating one-step experience to update the action-value function. This elegant planning strategy has been mostly explored in the tabular setting. The aim of this paper is to revisit sample-based planning, in stochastic and continuous domains with learned models. We first highlight the flexibility afforded by a model over Experience Replay (ER). Replay-based methods can be seen as stochastic planning methods that repeatedly sample from a buffer of recent agent-environment interactions and perform updates to improve data efficiency. We show that a model, as opposed to a replay buffer, is particularly useful for specifying which states to sample from during planning, such as predecessor states that propagate information in reverse from a state more quickly. We introduce a semi-parametric model learning approach, called Reweighted Experience Models (REMs), that makes it simple to sample next states or predecessors. We demonstrate that REM-Dyna exhibits similar advantages over replay-based methods in learning in continuous state problems, and that the performance gap grows when moving to stochastic domains, of increasing size.

##### Abstract (translated by Google)
基于模型的控制策略对于获得样本高效学习至关重要。 Dyna是一种自然交错学习和计划的规划范例，通过模拟一步体验来更新动作值功能。这种优雅的规划策略主要是在表格设置中进行探索。本文的目的是在具有学习模型的随机和连续领域重新审视基于样本的规划。我们首先强调模型在体验重播（ER）上提供的灵活性。基于回放的方法可以看作是随机规划方法，它可以从最近的代理 - 环境交互的缓冲区重复抽样，并执行更新以提高数据效率。我们表明，与重放缓冲区相反，模型对于指定在规划期间从哪个状态进行采样特别有用，例如更快地从状态反向传播信息的前驱状态。我们引入了一种名为Reweighted Experience Models（REMs）的半参数模型学习方法，可以很容易地对样品的下一个状态或前辈进行取样。我们证明REM-Dyna在连续状态问题的学习中表现出与基于重放的方法类似的优势，并且在向随机域扩大时性能差距会增大。

##### URL
[http://arxiv.org/abs/1806.04624](http://arxiv.org/abs/1806.04624)

##### PDF
[http://arxiv.org/pdf/1806.04624](http://arxiv.org/pdf/1806.04624)

