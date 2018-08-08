---
layout: post
title: "MCRM: Mother Compact Recurrent Memory A Biologically Inspired Recurrent Neural Network Architecture"
date: 2018-08-04 15:48:39
categories: arXiv_CV
tags: arXiv_CV RNN Relation
author: Abduallah Mohamed, Christian Claudel
mathjax: true
---

* content
{:toc}

##### Abstract
LSTMs and GRUs are the most common recurrent neural network architectures used to solve temporal sequence problems. The two architectures have differing data flows dealing with a common component called the cell state also referred to as the memory. We attempt to enhance the memory by presenting a biologically inspired modification that we call the Mother Compact Recurrent Memory MCRM. MCRMs are a type of a nested LSTM-GRU architecture where the cell state is the GRU's hidden state. The relationship between the womb and the fetus is analogous to the relationship between the LSTM and GRU inside MCRM in that the fetus is connected to its womb through the umbilical cord. The umbilical cord consists of two arteries and one vein. The two arteries are considered as an input to the fetus which is analogous to the concatenation of the forget gate and input gate from the LSTM. The vein is the output from the fetus which plays the role of the hidden state of the GRU. Because MCRMs has this type of nesting, MCRMs have a compact memory pattern consisting of neurons that act explicitly in both long-term and short-term fashions. For some specific tasks, empirical results show that MCRMs outperform previously used architectures.

##### Abstract (translated by Google)
LSTM和GRU是用于解决时间序列问题的最常见的递归神经网络架构。这两种体系结构具有不同的数据流，处理称为单元状态的公共组件，也称为存储器。我们尝试通过提供一种生物学启发的修改来增强记忆，我们称之为母体紧凑型复发记忆MCRM。 MCRM是一种嵌套的LSTM-GRU架构，其中单元状态是GRU的隐藏状态。子宫和胎儿之间的关系类似于MCRM内LSTM和GRU之间的关系，因为胎儿通过脐带连接到子宫。脐带由两条动脉和一条静脉组成。这两条动脉被认为是胎儿的输入，类似于来自LSTM的遗忘门和输入门的连接。静脉是胎儿的输出，其起着GRU隐藏状态的作用。由于MCRM具有这种类型的嵌套，因此MCRM具有紧凑的记忆模式，其由神经元组成，其以长期和短期方式明确地起作用。对于某些特定任务，实证结果表明MCRM优于以前使用的架构。

##### URL
[https://arxiv.org/abs/1808.02016](https://arxiv.org/abs/1808.02016)

##### PDF
[https://arxiv.org/pdf/1808.02016](https://arxiv.org/pdf/1808.02016)

