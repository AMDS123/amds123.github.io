---
layout: post
title: "Order Matters: Sequence to sequence for sets"
date: 2016-02-23 22:25:12
categories: arXiv_CL
tags: arXiv_CL GAN RNN Language_Model
author: Oriol Vinyals, Samy Bengio, Manjunath Kudlur
mathjax: true
---

* content
{:toc}

##### Abstract
Sequences have become first class citizens in supervised learning thanks to the resurgence of recurrent neural networks. Many complex tasks that require mapping from or to a sequence of observations can now be formulated with the sequence-to-sequence (seq2seq) framework which employs the chain rule to efficiently represent the joint probability of sequences. In many cases, however, variable sized inputs and/or outputs might not be naturally expressed as sequences. For instance, it is not clear how to input a set of numbers into a model where the task is to sort them; similarly, we do not know how to organize outputs when they correspond to random variables and the task is to model their unknown joint probability. In this paper, we first show using various examples that the order in which we organize input and/or output data matters significantly when learning an underlying model. We then discuss an extension of the seq2seq framework that goes beyond sequences and handles input sets in a principled way. In addition, we propose a loss which, by searching over possible orders during training, deals with the lack of structure of output sets. We show empirical evidence of our claims regarding ordering, and on the modifications to the seq2seq framework on benchmark language modeling and parsing tasks, as well as two artificial tasks -- sorting numbers and estimating the joint probability of unknown graphical models.

##### Abstract (translated by Google)
随着循环神经网络的复兴，序列已成为监督学习的一等公民。现在可以使用序列到序列（seq2seq）框架来制定许多需要从观察序列映射到观察序列或到观察序列的复杂任务，该框架使用链规则来高效地表示序列的联合概率。然而，在许多情况下，可变尺寸的输入和/或输出可能不会自然地表示为序列。例如，不清楚如何将一组数字输入到任务要分类的模型中;同样，我们不知道如何组织产出，当他们对应随机变量和任务是建模未知的联合概率。在本文中，我们首先使用各种示例来展示在学习基础模型时，我们组织输入和/或输出数据的顺序。然后我们讨论seq2seq框架的扩展，它超越了序列，并以原则的方式处理输入集合。此外，我们提出了一个损失，通过在培训期间搜索可能的订单来处理产出组合结构的不足。我们展示了关于排序的经验证据，以及对基准语言建模和解析任务的seq2seq框架的修改，以及两个人工任务 - 排序数字和估计未知图形模型的联合概率。

##### URL
[https://arxiv.org/abs/1511.06391](https://arxiv.org/abs/1511.06391)

##### PDF
[https://arxiv.org/pdf/1511.06391](https://arxiv.org/pdf/1511.06391)

