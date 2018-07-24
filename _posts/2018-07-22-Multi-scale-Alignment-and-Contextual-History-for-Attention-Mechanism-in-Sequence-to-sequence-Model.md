---
layout: post
title: "Multi-scale Alignment and Contextual History for Attention Mechanism in Sequence-to-sequence Model"
date: 2018-07-22 13:10:30
categories: arXiv_CL
tags: arXiv_CL Attention Speech_Recognition Recognition
author: Andros Tjandra, Sakriani Sakti, Satoshi Nakamura
mathjax: true
---

* content
{:toc}

##### Abstract
A sequence-to-sequence model is a neural network module for mapping two sequences of different lengths. The sequence-to-sequence model has three core modules: encoder, decoder, and attention. Attention is the bridge that connects the encoder and decoder modules and improves model performance in many tasks. In this paper, we propose two ideas to improve sequence-to-sequence model performance by enhancing the attention module. First, we maintain the history of the location and the expected context from several previous time-steps. Second, we apply multiscale convolution from several previous attention vectors to the current decoder state. We utilized our proposed framework for sequence-to-sequence speech recognition and text-to-speech systems. The results reveal that our proposed extension could improve performance significantly compared to a standard attention baseline.

##### Abstract (translated by Google)
序列到序列模型是用于映射两个不同长度的序列的神经网络模块。序列到序列模型有三个核心模块：编码器，解码器和注意力。注意力是连接编码器和解码器模块的桥梁，并在许多任务中提高模型性能。在本文中，我们提出了两个想法，通过增强注意力模块来改进序列到序列模型的性能。首先，我们从几个先前的时间步骤维护位置的历史和预期的上下文。其次，我们将多个先前注意向量的多尺度卷积应用于当前解码器状态。我们利用我们提出的序列到序列语音识别和文本到语音系统的框架。结果表明，与标准注意力基线相比，我们提出的扩展可以显着提高性能。

##### URL
[http://arxiv.org/abs/1807.08280](http://arxiv.org/abs/1807.08280)

##### PDF
[http://arxiv.org/pdf/1807.08280](http://arxiv.org/pdf/1807.08280)

