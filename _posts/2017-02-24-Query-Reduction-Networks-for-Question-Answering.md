---
layout: post
title: "Query-Reduction Networks for Question Answering"
date: 2017-02-24 19:59:01
categories: arXiv_CL
tags: arXiv_CL QA Inference RNN
author: Minjoon Seo, Sewon Min, Ali Farhadi, Hannaneh Hajishirzi
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we study the problem of question answering when reasoning over multiple facts is required. We propose Query-Reduction Network (QRN), a variant of Recurrent Neural Network (RNN) that effectively handles both short-term (local) and long-term (global) sequential dependencies to reason over multiple facts. QRN considers the context sentences as a sequence of state-changing triggers, and reduces the original query to a more informed query as it observes each trigger (context sentence) through time. Our experiments show that QRN produces the state-of-the-art results in bAbI QA and dialog tasks, and in a real goal-oriented dialog dataset. In addition, QRN formulation allows parallelization on RNN's time axis, saving an order of magnitude in time complexity for training and inference.

##### Abstract (translated by Google)
在本文中，我们研究问题回答的问题时，需要多个事实的推理。我们提出了查询 - 减少网络（QRN），这是递归神经网络（RNN）的一个变体，能够有效地处理短期（局部）和长期（全局）顺序依赖关系，以推理多个事实。 QRN将上下文句子视为一系列状态改变触发器，并将原始查询减少为随时间观察每个触发器（上下文句子）的更明智的查询。我们的实验显示QRN在bAbI QA和对话任务中以及在一个真正的面向目标的对话数据集中产生了最新的结果。此外，QRN公式允许RNN时间轴上的并行化，为训练和推理节省时间复杂度的一个数量级。

##### URL
[https://arxiv.org/abs/1606.04582](https://arxiv.org/abs/1606.04582)

##### PDF
[https://arxiv.org/pdf/1606.04582](https://arxiv.org/pdf/1606.04582)

