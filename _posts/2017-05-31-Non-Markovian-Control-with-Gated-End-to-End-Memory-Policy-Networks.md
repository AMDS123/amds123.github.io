---
layout: post
title: "Non-Markovian Control with Gated End-to-End Memory Policy Networks"
date: 2017-05-31 09:00:44
categories: arXiv_CV
tags: arXiv_CV Attention Reinforcement_Learning
author: Julien Perez, Tomi Silander
mathjax: true
---

* content
{:toc}

##### Abstract
Partially observable environments present an important open challenge in the domain of sequential control learning with delayed rewards. Despite numerous attempts during the two last decades, the majority of reinforcement learning algorithms and associated approximate models, applied to this context, still assume Markovian state transitions. In this paper, we explore the use of a recently proposed attention-based model, the Gated End-to-End Memory Network, for sequential control. We call the resulting model the Gated End-to-End Memory Policy Network. More precisely, we use a model-free value-based algorithm to learn policies for partially observed domains using this memory-enhanced neural network. This model is end-to-end learnable and it features unbounded memory. Indeed, because of its attention mechanism and associated non-parametric memory, the proposed model allows us to define an attention mechanism over the observation stream unlike recurrent models. We show encouraging results that illustrate the capability of our attention-based model in the context of the continuous-state non-stationary control problem of stock trading. We also present an OpenAI Gym environment for simulated stock exchange and explain its relevance as a benchmark for the field of non-Markovian decision process learning.

##### Abstract (translated by Google)
部分可观察的环境在延迟奖励的顺序控制学习领域提出了一个重要的公开挑战。尽管在过去的二十年中进行了大量的尝试，但大多数强化学习算法和相关的近似模型，仍然采用马尔可夫状态转换。在本文中，我们探讨了使用最近提出的基于注意的模型，门控端到端存储器网络，进行顺序控制。我们将所得到的模型称为Gated端到端内存策略网络。更确切地说，我们使用一个无模型的基于价值的算法来学习使用这个记忆增强的神经网络的部分观察域的策略。这个模型是端到端可学习的，它具有无限的内存。事实上，由于其注意机制和相关的非参数记忆，所提出的模型使得我们能够在观测流上定义一种关注机制，这与循环模型不同。我们展示了令人鼓舞的结果，这些结果说明了在股票交易的持续状态非平稳控制问题的背景下我们注意力模型的能力。我们还提供了一个用于模拟证券交易所的OpenAI健身房环境，并解释其作为非马尔可夫决策过程学习领域基准的相关性。

##### URL
[https://arxiv.org/abs/1705.10993](https://arxiv.org/abs/1705.10993)

##### PDF
[https://arxiv.org/pdf/1705.10993](https://arxiv.org/pdf/1705.10993)

