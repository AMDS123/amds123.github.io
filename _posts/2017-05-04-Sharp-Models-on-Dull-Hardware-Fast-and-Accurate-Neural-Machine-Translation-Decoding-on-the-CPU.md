---
layout: post
title: "Sharp Models on Dull Hardware: Fast and Accurate Neural Machine Translation Decoding on the CPU"
date: 2017-05-04 19:50:35
categories: arXiv_CL
tags: arXiv_CL NMT RNN
author: Jacob Devlin
mathjax: true
---

* content
{:toc}

##### Abstract
Attentional sequence-to-sequence models have become the new standard for machine translation, but one challenge of such models is a significant increase in training and decoding cost compared to phrase-based systems. Here, we focus on efficient decoding, with a goal of achieving accuracy close the state-of-the-art in neural machine translation (NMT), while achieving CPU decoding speed/throughput close to that of a phrasal decoder. We approach this problem from two angles: First, we describe several techniques for speeding up an NMT beam search decoder, which obtain a 4.4x speedup over a very efficient baseline decoder without changing the decoder output. Second, we propose a simple but powerful network architecture which uses an RNN (GRU/LSTM) layer at bottom, followed by a series of stacked fully-connected layers applied at every timestep. This architecture achieves similar accuracy to a deep recurrent model, at a small fraction of the training and decoding cost. By combining these techniques, our best system achieves a very competitive accuracy of 38.3 BLEU on WMT English-French NewsTest2014, while decoding at 100 words/sec on single-threaded CPU. We believe this is the best published accuracy/speed trade-off of an NMT system.

##### Abstract (translated by Google)
注意序列到序列模型已经成为机器翻译的新标准，但是与基于短语的系统相比，这种模型的一个挑战是训练和解码成本的显着增加。在这里，我们专注于高效的解码，目的在于实现接近神经机器翻译（NMT）的最新技术，同时实现接近于短语解码器的CPU解码速度/吞吐量。我们从两个角度来解决这个问题：首先，我们描述了几种用于加速NMT波束搜索解码器的技术，其在非常有效的基线解码器上获得4.4倍的加速而不改变解码器输出。其次，我们提出了一个简单而强大的网络架构，它在底部使用RNU（GRU / LSTM）层，随后在每个时间步应用一系列堆叠的全连接层。这种架构在深度循环模式下达到相似的精度，只需一小部分训练和解码成本。通过结合这些技术，我们的最佳系统在WMT英法新闻测试2014上实现了38.3 BLEU的非常有竞争力的精度，而在单线程CPU上以100字/秒的速度进行解码。我们相信这是NMT系统发布的最佳精度/速度折衷。

##### URL
[https://arxiv.org/abs/1705.01991](https://arxiv.org/abs/1705.01991)

##### PDF
[https://arxiv.org/pdf/1705.01991](https://arxiv.org/pdf/1705.01991)

