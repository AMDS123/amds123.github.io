---
layout: post
title: "A framework for automatic question generation from text using deep reinforcement learning"
date: 2018-08-15 04:05:02
categories: arXiv_CL
tags: arXiv_CL Reinforcement_Learning
author: Vishwajeet Kumar, Ganesh Ramakrishnan, Yuan-Fang Li
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic question generation (QG) is a useful yet challenging task in NLP. Recent neural network-based approaches represent the state-of-the-art in this task, but they are not without shortcomings. Firstly, these models lack the ability to handle rare words and the word repetition problem. Moreover, all previous works optimize the cross-entropy loss, which can induce inconsistencies between training (objective) and testing (evaluation measure). In this paper, we present a novel deep reinforcement learning based framework for automatic question generation. The generator of the framework is a sequence-to-sequence model, enhanced with the copy mechanism to handle the rare-words problem and the coverage mechanism to solve the word repetition problem. The evaluator model of the framework evaluates and assigns a reward to each predicted question. The overall model is trained by learning the parameters of the generator network which maximizes the reward. Our framework allows us to directly optimize any task-specific score including evaluation measures such as BLEU, GLEU, ROUGE-L, {\em etc.}, suitable for sequence to sequence tasks such as QG. Our comprehensive evaluation shows that our approach significantly outperforms state-of-the-art systems on the widely-used SQuAD benchmark in both automatic and human evaluation.

##### Abstract (translated by Google)
自动问题生成（QG）在NLP中是一项有用且具有挑战性的任务。最近基于神经网络的方法代表了这项任务的最新技术，但它们并非没有缺点。首先，这些模型缺乏处理稀有单词和单词重复问题的能力。此外，所有先前的工作都优化了交叉熵损失，这可能导致训练（目标）和测试（评估测量）之间的不一致。在本文中，我们提出了一种基于深度强化学习的自动问题生成框架。框架的生成器是序列到序列模型，增强了复制机制来处理稀有单词问题和覆盖机制来解决单词重复问题。框架的评估者模型评估并为每个预测的问题分配奖励。通过学习最大化奖励的发电机网络的参数来训练整个模型。我们的框架允许我们直接优化任何特定于任务的分数，包括评估测量，如BLEU，GLEU，ROUGE-L，{\ em等}，适用于序列到序列任务，如QG。我们的综合评估表明，在自动和人工评估中，我们的方法在广泛使用的SQuAD基准测试中明显优于最先进的系统。

##### URL
[http://arxiv.org/abs/1808.04961](http://arxiv.org/abs/1808.04961)

##### PDF
[http://arxiv.org/pdf/1808.04961](http://arxiv.org/pdf/1808.04961)

