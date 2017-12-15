---
layout: post
title: "A Comprehensive Study of Deep Bidirectional LSTM RNNs for Acoustic Modeling in Speech Recognition"
date: 2017-03-29 08:08:29
categories: arXiv_CL
tags: arXiv_CL Regularization Speech_Recognition Optimization RNN Relation Recognition
author: Albert Zeyer, Patrick Doetsch, Paul Voigtlaender, Ralf Schlüter, Hermann Ney
mathjax: true
---

* content
{:toc}

##### Abstract
We present a comprehensive study of deep bidirectional long short-term memory (LSTM) recurrent neural network (RNN) based acoustic models for automatic speech recognition (ASR). We study the effect of size and depth and train models of up to 8 layers. We investigate the training aspect and study different variants of optimization methods, batching, truncated backpropagation, different regularization techniques such as dropout and $L_2$ regularization, and different gradient clipping variants. The major part of the experimental analysis was performed on the Quaero corpus. Additional experiments also were performed on the Switchboard corpus. Our best LSTM model has a relative improvement in word error rate of over 14\% compared to our best feed-forward neural network (FFNN) baseline on the Quaero task. On this task, we get our best result with an 8 layer bidirectional LSTM and we show that a pretraining scheme with layer-wise construction helps for deep LSTMs. Finally we compare the training calculation time of many of the presented experiments in relation with recognition performance. All the experiments were done with RETURNN, the RWTH extensible training framework for universal recurrent neural networks in combination with RASR, the RWTH ASR toolkit.

##### Abstract (translated by Google)
我们提出了深度双向长时间记忆（LSTM）递归神经网络（RNN）基于声学模型的自动语音识别（ASR）的综合研究。我们研究尺寸和深度的影响，并培训多达8层的模型。我们研究了训练方面，研究了不同的优化方法，批处理，截断反向传播，不同的正则化技术，如辍学和$ L_2 $正则化，以及不同的梯度剪切变体。实验分析的主要部分是在Quaero语料库上进行的。还在交换机语料库上进行了另外的实验。与我们在Quaero任务中的最佳前馈神经网络（FFNN）基线相比，我们最好的LSTM模型在词汇错误率方面的相对改进超过14％。在这个任务上，我们用8层双向LSTM得到了最好的结果，并且我们展示了一个层层构造的预训练方案有助于深LSTM。最后，我们比较了许多提出的实验的训练计算时间与识别性能的关系。所有的实验都是通过RETURNN（RWTH ASR工具包）与RASR（通用递归神经网络）的RWTH可扩展训练框架来完成的。

##### URL
[https://arxiv.org/abs/1606.06871](https://arxiv.org/abs/1606.06871)

##### PDF
[https://arxiv.org/pdf/1606.06871](https://arxiv.org/pdf/1606.06871)

