---
layout: post
title: "GroupReduce: Block-Wise Low-Rank Approximation for Neural Language Model Shrinking"
date: 2018-06-18 23:08:15
categories: arXiv_AI
tags: arXiv_AI Embedding RNN Language_Model
author: Patrick H. Chen, Si Si, Yang Li, Ciprian Chelba, Cho-jui Hsieh
mathjax: true
---

* content
{:toc}

##### Abstract
Model compression is essential for serving large deep neural nets on devices with limited resources or applications that require real-time responses. As a case study, a state-of-the-art neural language model usually consists of one or more recurrent layers sandwiched between an embedding layer used for representing input tokens and a softmax layer for generating output tokens. For problems with a very large vocabulary size, the embedding and the softmax matrices can account for more than half of the model size. For instance, the bigLSTM model achieves state-of- the-art performance on the One-Billion-Word (OBW) dataset with around 800k vocabulary, and its word embedding and softmax matrices use more than 6GBytes space, and are responsible for over 90% of the model parameters. In this paper, we propose GroupReduce, a novel compression method for neural language models, based on vocabulary-partition (block) based low-rank matrix approximation and the inherent frequency distribution of tokens (the power-law distribution of words). The experimental results show our method can significantly outperform traditional compression methods such as low-rank approximation and pruning. On the OBW dataset, our method achieved 6.6 times compression rate for the embedding and softmax matrices, and when combined with quantization, our method can achieve 26 times compression rate, which translates to a factor of 12.8 times compression for the entire model with very little degradation in perplexity.

##### Abstract (translated by Google)
模型压缩对于在资源有限或需要实时响应的应用程序的设备上提供大型深度神经网络至关重要。作为案例研究，现有技术的神经语言模型通常由夹在用于表示输入令牌的嵌入层和用于生成输出令牌的softmax层之间的一个或多个递归层组成。对于词汇量很大的问题，嵌入和softmax矩阵可能占到模型大小的一半以上。例如，bigLSTM模型在大约800k词汇量的十亿字（OBW）数据集上实现了最先进的性能，其词嵌入和softmax矩阵使用超过6GBytes的空间，并且负责超过90 ％的模型参数。在本文中，我们基于基于词汇分区（块）的低秩矩阵近似和标记的固有频率分布（词的幂律分布），提出GroupReduce，一种用于神经语言模型的新型压缩方法。实验结果表明，我们的方法可以显着优于传统的压缩方法，如低秩逼近和修剪。在OBW数据集中，我们的方法对于嵌入和softmax矩阵实现了6.6倍的压缩率，并且当与量化结合时，我们的方法可以实现26倍的压缩率，这相当于整个模型的12.8倍压缩因子，几乎没有在困惑中退化。

##### URL
[http://arxiv.org/abs/1806.06950](http://arxiv.org/abs/1806.06950)

##### PDF
[http://arxiv.org/pdf/1806.06950](http://arxiv.org/pdf/1806.06950)

