---
layout: post
title: "End-to-End Attention-based Large Vocabulary Speech Recognition"
date: 2016-03-14 23:07:20
categories: arXiv_CL
tags: arXiv_CL Attention Speech_Recognition RNN Language_Model Prediction Recognition
author: Dzmitry Bahdanau, Jan Chorowski, Dmitriy Serdyuk, Philemon Brakel, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Many of the current state-of-the-art Large Vocabulary Continuous Speech Recognition Systems (LVCSR) are hybrids of neural networks and Hidden Markov Models (HMMs). Most of these systems contain separate components that deal with the acoustic modelling, language modelling and sequence decoding. We investigate a more direct approach in which the HMM is replaced with a Recurrent Neural Network (RNN) that performs sequence prediction directly at the character level. Alignment between the input features and the desired character sequence is learned automatically by an attention mechanism built into the RNN. For each predicted character, the attention mechanism scans the input sequence and chooses relevant frames. We propose two methods to speed up this operation: limiting the scan to a subset of most promising frames and pooling over time the information contained in neighboring frames, thereby reducing source sequence length. Integrating an n-gram language model into the decoding process yields recognition accuracies similar to other HMM-free RNN-based approaches.

##### Abstract (translated by Google)
许多目前最先进的大型词汇连续语音识别系统（LVCSR）是神经网络和隐马尔可夫模型（HMM）的混合体。这些系统中的大多数都包含独立的组件，用于处理声学建模，语言建模和序列解码。我们调查一个更直接的方法，其中HMM被直接在字符级别执行序列预测的递归神经网络（RNN）代替。输入特征和所需字符序列之间的对齐由内置于RNN中的注意机制自动学习。对于每个预测字符，注意机制扫描输入序列并选择相关的帧。我们提出了两种方法来加速这一操作：将扫描限制为最有希望的帧的子集并随时间汇集相邻帧中包含的信息，由此减少源序列长度。将n-gram语言模型集成到解码过程中产生类似于其他基于HMM的基于RNN的方法的识别精度。

##### URL
[https://arxiv.org/abs/1508.04395](https://arxiv.org/abs/1508.04395)

##### PDF
[https://arxiv.org/pdf/1508.04395](https://arxiv.org/pdf/1508.04395)

