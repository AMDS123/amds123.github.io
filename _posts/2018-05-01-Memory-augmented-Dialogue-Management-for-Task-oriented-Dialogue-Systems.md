---
layout: post
title: "Memory-augmented Dialogue Management for Task-oriented Dialogue Systems"
date: 2018-05-01 02:14:00
categories: arXiv_CL
tags: arXiv_CL Attention RNN
author: Zheng Zhang, Minlie Huang, Zhongzhou Zhao, Feng Ji, Haiqing Chen, Xiaoyan Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
Dialogue management (DM) decides the next action of a dialogue system according to the current dialogue state, and thus plays a central role in task-oriented dialogue systems. Since dialogue management requires to have access to not only local utterances, but also the global semantics of the entire dialogue session, modeling the long-range history information is a critical issue. To this end, we propose a novel Memory-Augmented Dialogue management model (MAD) which employs a memory controller and two additional memory structures, i.e., a slot-value memory and an external memory. The slot-value memory tracks the dialogue state by memorizing and updating the values of semantic slots (for instance, cuisine, price, and location), and the external memory augments the representation of hidden states of traditional recurrent neural networks through storing more context information. To update the dialogue state efficiently, we also propose slot-level attention on user utterances to extract specific semantic information for each slot. Experiments show that our model can obtain state-of-the-art performance and outperforms existing baselines.

##### Abstract (translated by Google)
对话管理（DM）根据当前对话状态决定对话系统的下一步行动，因此在面向任务的对话系统中发挥核心作用。由于对话管理不仅需要访问当地话语，还需要访问整个对话会议的全球语义，因此建模远程历史信息是一个关键问题。为此，我们提出了一种新型的Memory-Augmented Dialogue管理模型（MAD），它使用一个存储器控制器和两个额外的存储器结构，即一个槽值存储器和一个外部存储器。时隙值存储器通过记忆和更新语义槽的值（例如美食，价格和位置）来跟踪对话状态，并且外部存储器通过存储更多的上下文信息来增强传统递归神经网络的隐藏状态的表示。为了有效地更新对话状态，我们还提出对用户话语的时间片级关注以提取每个时隙的特定语义信息。实验表明，我们的模型可以获得最先进的性能，并且胜过现有的基线。

##### URL
[https://arxiv.org/abs/1805.00150](https://arxiv.org/abs/1805.00150)

##### PDF
[https://arxiv.org/pdf/1805.00150](https://arxiv.org/pdf/1805.00150)

