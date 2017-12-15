---
layout: post
title: "BlackOut: Speeding up Recurrent Neural Network Language Models With Very Large Vocabularies"
date: 2016-03-31 17:37:25
categories: arXiv_CL
tags: arXiv_CL RNN Language_Model
author: Shihao Ji, S. V. N. Vishwanathan, Nadathur Satish, Michael J. Anderson, Pradeep Dubey
mathjax: true
---

* content
{:toc}

##### Abstract
We propose BlackOut, an approximation algorithm to efficiently train massive recurrent neural network language models (RNNLMs) with million word vocabularies. BlackOut is motivated by using a discriminative loss, and we describe a new sampling strategy which significantly reduces computation while improving stability, sample efficiency, and rate of convergence. One way to understand BlackOut is to view it as an extension of the DropOut strategy to the output layer, wherein we use a discriminative training loss and a weighted sampling scheme. We also establish close connections between BlackOut, importance sampling, and noise contrastive estimation (NCE). Our experiments, on the recently released one billion word language modeling benchmark, demonstrate scalability and accuracy of BlackOut; we outperform the state-of-the art, and achieve the lowest perplexity scores on this dataset. Moreover, unlike other established methods which typically require GPUs or CPU clusters, we show that a carefully implemented version of BlackOut requires only 1-10 days on a single machine to train a RNNLM with a million word vocabulary and billions of parameters on one billion words. Although we describe BlackOut in the context of RNNLM training, it can be used to any networks with large softmax output layers.

##### Abstract (translated by Google)
我们提出了BlackOut（一种近似算法，用于有效训练具有百万字词汇的大规模递归神经网络语言模型（RNNLM））。 BlackOut的动机是使用判别式损失，并且我们描述了一个新的采样策略，在提高稳定性，采样效率和收敛速度的同时，大大减少了计算量。理解BlackOut的一种方法是将其视为DropOut策略到输出层的扩展，其中我们使用判别式训练丢失和加权抽样方案。我们还建立了BlackOut，重要性抽样和噪声对比估计（NCE）之间的密切联系。我们在最近发布的十亿字语言建模基准测试中的实验展示了BlackOut的可扩展性和准确性;我们胜过最先进的技术，并在这个数据集上获得最低的困惑分数。而且，与通常需要GPU或CPU集群的其他已建立的方法不同，我们表明，仔细实施的BlackOut版本仅需要1-10天就可以在单个机器上训练一个带有百万字词汇和十亿个字的十亿个参数的RNNLM 。尽管我们在RNNLM训练的背景下描述了BlackOut，但它可以用于任何具有较大softmax输出层的网络。

##### URL
[https://arxiv.org/abs/1511.06909](https://arxiv.org/abs/1511.06909)

##### PDF
[https://arxiv.org/pdf/1511.06909](https://arxiv.org/pdf/1511.06909)

