---
layout: post
title: "Frustratingly Short Attention Spans in Neural Language Modeling"
date: 2017-02-15 09:45:23
categories: arXiv_SD
tags: arXiv_SD Attention Language_Model
author: Michał Daniluk, Tim Rocktäschel, Johannes Welbl, Sebastian Riedel
mathjax: true
---

* content
{:toc}

##### Abstract
Neural language models predict the next token using a latent representation of the immediate token history. Recently, various methods for augmenting neural language models with an attention mechanism over a differentiable memory have been proposed. For predicting the next token, these models query information from a memory of the recent history which can facilitate learning mid- and long-range dependencies. However, conventional attention mechanisms used in memory-augmented neural language models produce a single output vector per time step. This vector is used both for predicting the next token as well as for the key and value of a differentiable memory of a token history. In this paper, we propose a neural language model with a key-value attention mechanism that outputs separate representations for the key and value of a differentiable memory, as well as for encoding the next-word distribution. This model outperforms existing memory-augmented neural language models on two corpora. Yet, we found that our method mainly utilizes a memory of the five most recent output representations. This led to the unexpected main finding that a much simpler model based only on the concatenation of recent output representations from previous time steps is on par with more sophisticated memory-augmented neural language models.

##### Abstract (translated by Google)
神经语言模型使用即时令牌历史的潜在表示来预测下一个令牌。近来，已经提出了用于增强具有可微分存储器的关注机制的神经语言模型的各种方法。为了预测下一个标记，这些模型从最近历史的记忆中查询信息，这有助于学习中长程依赖。然而，在记忆增强的神经语言模型中使用的传统关注机制每个时间步长产生单个输出向量。该向量既用于预测下一个标记，也用于标记历史记录的可区分内存的键和值。在本文中，我们提出了一个具有键值注意机制的神经语言模型，它输出可微内存的关键和值的单独表示，以及编码下一个字的分布。这个模型比两个语料库中已有的记忆增强的神经语言模型更胜一筹。然而，我们发现我们的方法主要是利用五个最近输出表示的记忆。这导致了一个意想不到的主要发现，即仅基于来自先前时间步骤的最近输出表示的级联的更简单的模型与更复杂的记忆增强神经语言模型相当。

##### URL
[https://arxiv.org/abs/1702.04521](https://arxiv.org/abs/1702.04521)

##### PDF
[https://arxiv.org/pdf/1702.04521](https://arxiv.org/pdf/1702.04521)

