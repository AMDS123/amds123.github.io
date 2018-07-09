---
layout: post
title: "Sliced Recurrent Neural Networks"
date: 2018-07-06 07:31:13
categories: arXiv_CL
tags: arXiv_CL Sentiment RNN
author: Zeping Yu, Gongshen Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks have achieved great success in many NLP tasks. However, they have difficulty in parallelization because of the recurrent structure, so it takes much time to train RNNs. In this paper, we introduce sliced recurrent neural networks (SRNNs), which could be parallelized by slicing the sequences into many subsequences. SRNNs have the ability to obtain high-level information through multiple layers with few extra parameters. We prove that the standard RNN is a special case of the SRNN when we use linear activation functions. Without changing the recurrent units, SRNNs are 136 times as fast as standard RNNs and could be even faster when we train longer sequences. Experiments on six largescale sentiment analysis datasets show that SRNNs achieve better performance than standard RNNs.

##### Abstract (translated by Google)
循环神经网络在许多NLP任务中取得了巨大成功。然而，由于结构的重复性，它们难以并行化，因此需要花费很多时间来训练RNN。在本文中，我们介绍了切片的递归神经网络（SRNN），它可以通过将序列切割成许多子序列来并行化。 SRNN能够通过多个层获得高级信息，只需很少的额外参数。我们证明了当我们使用线性激活函数时，标准RNN是SRNN的特例。在不改变循环单位的情况下，SRNN的速度是标准RNN的136倍，并且当我们训练更长的序列时SRNN可能更快。对六个大规模情感分析数据集的实验表明，SRNN比标准RNN具有更好的性能。

##### URL
[http://arxiv.org/abs/1807.02291](http://arxiv.org/abs/1807.02291)

##### PDF
[http://arxiv.org/pdf/1807.02291](http://arxiv.org/pdf/1807.02291)

