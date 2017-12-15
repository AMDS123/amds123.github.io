---
layout: post
title: "A Sequence-to-Sequence Model for User Simulation in Spoken Dialogue Systems"
date: 2016-06-30 22:51:00
categories: arXiv_CL
tags: arXiv_CL Tracking
author: Layla El Asri, Jing He, Kaheer Suleman
mathjax: true
---

* content
{:toc}

##### Abstract
User simulation is essential for generating enough data to train a statistical spoken dialogue system. Previous models for user simulation suffer from several drawbacks, such as the inability to take dialogue history into account, the need of rigid structure to ensure coherent user behaviour, heavy dependence on a specific domain, the inability to output several user intentions during one dialogue turn, or the requirement of a summarized action space for tractability. This paper introduces a data-driven user simulator based on an encoder-decoder recurrent neural network. The model takes as input a sequence of dialogue contexts and outputs a sequence of dialogue acts corresponding to user intentions. The dialogue contexts include information about the machine acts and the status of the user goal. We show on the Dialogue State Tracking Challenge 2 (DSTC2) dataset that the sequence-to-sequence model outperforms an agenda-based simulator and an n-gram simulator, according to F-score. Furthermore, we show how this model can be used on the original action space and thereby models user behaviour with finer granularity.

##### Abstract (translated by Google)
用户模拟对于生成足够的数据来训练统计口语对话系统是必不可少的。以前的用户模拟模型存在几个缺点，例如无法考虑对话历史，需要严格的结构来确保连贯的用户行为，严重依赖于特定的领域，在一个对话转向期间不能输出多个用户意图或者为了便于处理而要求总结的行动空间。本文介绍了一种基于编解码器递归神经网络的数据驱动用户仿真器。该模型将一系列对话上下文作为输入，并输出对应于用户意图的一系列对话行为。对话上下文包括有关机器动作和用户目标状态的信息。我们在对话状态跟踪挑战2（DSTC2）数据集上展示了根据F评分，序列 - 序列模型优于基于议程的模拟器和n-gram模拟器。此外，我们还展示了如何将这个模型用于原始行为空间，从而以更细的粒度模拟用户行为。

##### URL
[https://arxiv.org/abs/1607.00070](https://arxiv.org/abs/1607.00070)

##### PDF
[https://arxiv.org/pdf/1607.00070](https://arxiv.org/pdf/1607.00070)

