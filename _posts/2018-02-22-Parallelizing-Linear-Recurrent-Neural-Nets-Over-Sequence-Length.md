---
layout: post
title: "Parallelizing Linear Recurrent Neural Nets Over Sequence Length"
date: 2018-02-22 05:38:25
categories: arXiv_AI
tags: arXiv_AI Inference RNN Classification
author: Eric Martin, Chris Cundy
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks (RNNs) are widely used to model sequential data but their non-linear dependencies between sequence elements prevent parallelizing training over sequence length. We show the training of RNNs with only linear sequential dependencies can be parallelized over the sequence length using the parallel scan algorithm, leading to rapid training on long sequences even with small minibatch size. We develop a parallel linear recurrence CUDA kernel and show that it can be applied to immediately speed up training and inference of several state of the art RNN architectures by up to 9x. We abstract recent work on linear RNNs into a new framework of linear surrogate RNNs and develop a linear surrogate model for the long short-term memory unit, the GILR-LSTM, that utilizes parallel linear recurrence. We extend sequence learning to new extremely long sequence regimes that were previously out of reach by successfully training a GILR-LSTM on a synthetic sequence classification task with a one million timestep dependency.

##### Abstract (translated by Google)
递归神经网络（RNN）广泛用于序列数据建模，但它们之间的非线性相关性阻碍了序列长度上的训练并行化。我们展示了只使用线性顺序依赖性的RNN训练可以使用并行扫描算法在序列长度上并行化，从而即使在小批量大小的情况下也可以对长序列进行快速训练。我们开发了一个并行线性递归CUDA内核，并表明它可以用于立即加速对多种先进RNN体系结构的训练和推断，最高可达9x。我们将最近关于线性RNN的工作抽象为线性替代RNN的新框架，并为长期短期记忆单元GILR-LSTM开发线性替代模型，该模型利用平行线性递归。我们将序列学习扩展到以前无法实现的新的超长序列机制，这是通过在具有100万次时间依赖性的合成序列分类任务上成功训练GILR-LSTM来实现的。

##### URL
[http://arxiv.org/abs/1709.04057](http://arxiv.org/abs/1709.04057)

##### PDF
[http://arxiv.org/pdf/1709.04057](http://arxiv.org/pdf/1709.04057)

