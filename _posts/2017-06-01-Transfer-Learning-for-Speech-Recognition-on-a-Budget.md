---
layout: post
title: "Transfer Learning for Speech Recognition on a Budget"
date: 2017-06-01 13:33:54
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition CNN Transfer_Learning Recognition
author: Julius Kunze, Louis Kirsch, Ilia Kurenkov, Andreas Krug, Jens Johannsmeier, Sebastian Stober
mathjax: true
---

* content
{:toc}

##### Abstract
End-to-end training of automated speech recognition (ASR) systems requires massive data and compute resources. We explore transfer learning based on model adaptation as an approach for training ASR models under constrained GPU memory, throughput and training data. We conduct several systematic experiments adapting a Wav2Letter convolutional neural network originally trained for English ASR to the German language. We show that this technique allows faster training on consumer-grade resources while requiring less training data in order to achieve the same accuracy, thereby lowering the cost of training ASR models in other languages. Model introspection revealed that small adaptations to the network's weights were sufficient for good performance, especially for inner layers.

##### Abstract (translated by Google)
自动语音识别（ASR）系统的端到端培训需要大量的数据和计算资源。我们探索了基于模型自适应的转移学习，作为在受约束的GPU内存，吞吐量和训练数据下训练ASR模型的一种方法。我们进行了几个系统的实验，使最初接受英语ASR训练的Wav2Letter卷积神经网络适应德语。我们表明，这种技术允许更快的消费级资源培训，同时需要较少的培训数据，以达到相同的准确性，从而降低其他语言培训ASR模型的成本。模型内省显示，对网络权重的小适应足以获得良好的性能，特别是对于内层。

##### URL
[https://arxiv.org/abs/1706.00290](https://arxiv.org/abs/1706.00290)

##### PDF
[https://arxiv.org/pdf/1706.00290](https://arxiv.org/pdf/1706.00290)

