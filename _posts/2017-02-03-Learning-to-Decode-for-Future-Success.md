---
layout: post
title: "Learning to Decode for Future Success"
date: 2017-02-03 21:11:31
categories: arXiv_SD
tags: arXiv_SD Summarization
author: Jiwei Li, Will Monroe, Dan Jurafsky
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a simple, general strategy to manipulate the behavior of a neural decoder that enables it to generate outputs that have specific properties of interest (e.g., sequences of a pre-specified length). The model can be thought of as a simple version of the actor-critic model that uses an interpolation of the actor (the MLE-based token generation policy) and the critic (a value function that estimates the future values of the desired property) for decision making. We demonstrate that the approach is able to incorporate a variety of properties that cannot be handled by standard neural sequence decoders, such as sequence length and backward probability (probability of sources given targets), in addition to yielding consistent improvements in abstractive summarization and machine translation when the property to be optimized is BLEU or ROUGE scores.

##### Abstract (translated by Google)
我们引入一个简单的通用策略来操纵神经解码器的行为，使其能够生成具有特定感兴趣属性（例如，预定长度的序列）的输出。该模型可以被认为是一个简单版本的actor-critic模型，它使用了actor的插值（基于MLE的token生成策略）和批评者（估算所需属性未来值的值函数）做决定。我们证明，这个方法能够结合标准的神经序列解码器无法处理的各种属性，如序列长度和反向概率（源给定目标的概率），以及在抽象汇总和机器翻译中产生一致的改进当被优化的财产是BLEU或ROUGE时。

##### URL
[https://arxiv.org/abs/1701.06549](https://arxiv.org/abs/1701.06549)

##### PDF
[https://arxiv.org/pdf/1701.06549](https://arxiv.org/pdf/1701.06549)

