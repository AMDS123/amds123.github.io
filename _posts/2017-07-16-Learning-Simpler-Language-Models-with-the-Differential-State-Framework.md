---
layout: post
title: "Learning Simpler Language Models with the Differential State Framework"
date: 2017-07-16 22:27:29
categories: arXiv_SD
tags: arXiv_SD RNN Language_Model
author: Alexander G. Ororbia II, Tomas Mikolov, David Reitter
mathjax: true
---

* content
{:toc}

##### Abstract
Learning useful information across long time lags is a critical and difficult problem for temporal neural models in tasks such as language modeling. Existing architectures that address the issue are often complex and costly to train. The Differential State Framework (DSF) is a simple and high-performing design that unifies previously introduced gated neural models. DSF models maintain longer-term memory by learning to interpolate between a fast-changing data-driven representation and a slowly changing, implicitly stable state. This requires hardly any more parameters than a classical, simple recurrent network. Within the DSF framework, a new architecture is presented, the Delta-RNN. In language modeling at the word and character levels, the Delta-RNN outperforms popular complex architectures, such as the Long Short Term Memory (LSTM) and the Gated Recurrent Unit (GRU), and, when regularized, performs comparably to several state-of-the-art baselines. At the subword level, the Delta-RNN's performance is comparable to that of complex gated architectures.

##### Abstract (translated by Google)
在长时间滞后的情况下学习有用信息是时态神经模型在诸如语言建模等任务中的关键和难题。解决这个问题的现有体系结构往往是复杂而昂贵的培训。差分状态框架（DSF）是一种简单且高性能的设计，它将先前引入的门控神经模型统一起来。通过学习在快速变化的数据驱动表示和缓慢变化的隐式稳定状态之间进行插值，DSF模型保持较长时间的记忆。这几乎不需要比经典，简单的经常性网络更多的参数。在DSF框架内，提出了一种新的架构Delta-RNN。在词汇和字符级别的语言建模中，Delta-RNN比长期短期记忆（LSTM）和门控循环单元（GRU）等流行的复杂体系结构优胜，并且在规则化时，最先进的基线。在子字级，Delta-RNN的性能与复杂的门控架构相当。

##### URL
[https://arxiv.org/abs/1703.08864](https://arxiv.org/abs/1703.08864)

##### PDF
[https://arxiv.org/pdf/1703.08864](https://arxiv.org/pdf/1703.08864)

