---
layout: post
title: "Multi-Hop Knowledge Graph Reasoning with Reward Shaping"
date: 2018-08-31 01:55:09
categories: arXiv_AI
tags: arXiv_AI Knowledge_Graph Knowledge QA Reinforcement_Learning Embedding Inference
author: Xi Victoria Lin, Richard Socher, Caiming Xiong
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-hop reasoning is an effective approach for query answering (QA) over incomplete knowledge graphs (KGs). The problem can be formulated in a reinforcement learning (RL) setup, where a policy-based agent sequentially extends its inference path until it reaches a target. However, in an incomplete KG environment, the agent receives low-quality rewards corrupted by false negatives in the training data, which harms generalization at test time. Furthermore, since no golden action sequence is used for training, the agent can be misled by spurious search trajectories that incidentally lead to the correct answer. We propose two modeling advances to address both issues: (1) we reduce the impact of false negative supervision by adopting a pretrained one-hop embedding model to estimate the reward of unobserved facts; (2) we counter the sensitivity to spurious paths of on-policy RL by forcing the agent to explore a diverse set of paths using randomly generated edge masks. Our approach significantly improves over existing path-based KGQA models on several benchmark datasets and is comparable or better than embedding-based models.

##### Abstract (translated by Google)
多跳推理是针对不完整知识图（KG）的查询应答（QA）的有效方法。该问题可以在强化学习（RL）设置中制定，其中基于策略的代理顺序地扩展其推理路径直到其到达目标。然而，在不完整的KG环境中，代理接收到由训练数据中的假阴性破坏的低质量奖励，这在测试时损害了泛化。此外，由于没有使用黄金动作序列进行训练，因此虚拟搜索轨迹会误导代理，从而导致正确的答案。我们提出了两个建模进展来解决这两个问题：（1）通过采用预训练的单跳嵌入模型来估计未被观察到的事实的回报，从而减少假阴性监督的影响; （2）我们通过强制代理使用随机生成的边掩码探索不同的路径集来抵消对策略RL的虚假路径的敏感性。我们的方法显着改善了几个基准数据集上现有的基于路径的KGQA模型，并且与基于嵌入的模型相当或更好。

##### URL
[http://arxiv.org/abs/1808.10568](http://arxiv.org/abs/1808.10568)

##### PDF
[http://arxiv.org/pdf/1808.10568](http://arxiv.org/pdf/1808.10568)

