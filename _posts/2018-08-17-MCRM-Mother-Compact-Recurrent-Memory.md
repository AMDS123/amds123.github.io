---
layout: post
title: "MCRM: Mother Compact Recurrent Memory"
date: 2018-08-17 06:00:41
categories: arXiv_CV
tags: arXiv_CV RNN
author: Abduallah A. Mohamed, Christian Claudel
mathjax: true
---

* content
{:toc}

##### Abstract
LSTMs and GRUs are the most common recurrent neural network architectures used to solve temporal sequence problems. The two architectures have differing data flows dealing with a common component called the cell state (also referred to as the memory). We attempt to enhance the memory by presenting a modification that we call the Mother Compact Recurrent Memory (MCRM). MCRMs are a type of a nested LSTM-GRU architecture where the cell state is the GRU hidden state. The concatenation of the forget gate and input gate interactions from the LSTM are considered an input to the GRU cell. Because MCRMs has this type of nesting, MCRMs have a compact memory pattern consisting of neurons that acts explicitly in both long-term and short-term fashions. For some specific tasks, empirical results show that MCRMs outperform previously used architectures.

##### Abstract (translated by Google)
LSTM和GRU是用于解决时间序列问题的最常见的递归神经网络架构。这两种体系结构具有不同的数据流，处理称为单元状态的公共组件（也称为存储器）。我们尝试通过提供一种称为Mother Compact Recurrent Memory（MCRM）的修改来增强内存。 MCRM是一种嵌套的LSTM-GRU架构，其中单元状态是GRU隐藏状态。来自LSTM的遗忘门和输入门相互作用的串联被认为是GRU单元的输入。因为MCRM具有这种类型的嵌套，所以MCRM具有由神经元组成的紧凑存储器模式，其以长期和短期方式明确地起作用。对于某些特定任务，实证结果表明MCRM优于以前使用的架构。

##### URL
[https://arxiv.org/abs/1808.02016](https://arxiv.org/abs/1808.02016)

##### PDF
[https://arxiv.org/pdf/1808.02016](https://arxiv.org/pdf/1808.02016)

