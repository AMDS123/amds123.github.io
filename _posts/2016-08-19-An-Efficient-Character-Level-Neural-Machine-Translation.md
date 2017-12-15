---
layout: post
title: "An Efficient Character-Level Neural Machine Translation"
date: 2016-08-19 06:49:32
categories: arXiv_CL
tags: arXiv_CL Attention
author: Shenjian Zhao, Zhihua Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Neural machine translation aims at building a single large neural network that can be trained to maximize translation performance. The encoder-decoder architecture with an attention mechanism achieves a translation performance comparable to the existing state-of-the-art phrase-based systems on the task of English-to-French translation. However, the use of large vocabulary becomes the bottleneck in both training and improving the performance. In this paper, we propose an efficient architecture to train a deep character-level neural machine translation by introducing a decimator and an interpolator. The decimator is used to sample the source sequence before encoding while the interpolator is used to resample after decoding. Such a deep model has two major advantages. It avoids the large vocabulary issue radically; at the same time, it is much faster and more memory-efficient in training than conventional character-based models. More interestingly, our model is able to translate the misspelled word like human beings.

##### Abstract (translated by Google)
神经机器翻译旨在建立一个单一的大型神经网络，可以训练最大限度地提高翻译表现。具有关注机制的编码器 - 解码器体系结构实现了与英语至法语翻译任务中现有的最先进的基于短语的系统相媲美的翻译性能。然而，大量词汇的使用成为训练和提高表现的瓶颈。在本文中，我们提出了一种高效的体系结构，通过引入一个抽取器和一个插值器来训练深层次的字符级神经机器翻译。抽取器用于在编码之前对源序列进行采样，而插值器用于在解码之后重新采样。这样一个深刻的模型有两个主要的优点。它从根本上避免了大量的词汇问题;与传统的基于字符的模型相比，训练速度更快，记忆效率更高。更有趣的是，我们的模型能够像人一样翻译拼错的单词。

##### URL
[https://arxiv.org/abs/1608.04738](https://arxiv.org/abs/1608.04738)

##### PDF
[https://arxiv.org/pdf/1608.04738](https://arxiv.org/pdf/1608.04738)

