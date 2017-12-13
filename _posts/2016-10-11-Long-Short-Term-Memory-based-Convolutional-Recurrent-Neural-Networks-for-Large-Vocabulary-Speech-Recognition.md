---
layout: post
title: "Long Short-Term Memory based Convolutional Recurrent Neural Networks for Large Vocabulary Speech Recognition"
date: 2016-10-11 02:48:13
categories: arXiv_CV
tags: arXiv_CV GAN Speech_Recognition CNN RNN Recognition
author: Xiangang Li, Xihong Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Long short-term memory (LSTM) recurrent neural networks (RNNs) have been shown to give state-of-the-art performance on many speech recognition tasks, as they are able to provide the learned dynamically changing contextual window of all sequence history. On the other hand, the convolutional neural networks (CNNs) have brought significant improvements to deep feed-forward neural networks (FFNNs), as they are able to better reduce spectral variation in the input signal. In this paper, a network architecture called as convolutional recurrent neural network (CRNN) is proposed by combining the CNN and LSTM RNN. In the proposed CRNNs, each speech frame, without adjacent context frames, is organized as a number of local feature patches along the frequency axis, and then a LSTM network is performed on each feature patch along the time axis. We train and compare FFNNs, LSTM RNNs and the proposed LSTM CRNNs at various number of configurations. Experimental results show that the LSTM CRNNs can exceed state-of-the-art speech recognition performance.

##### Abstract (translated by Google)
长时间记忆（LSTM）递归神经网络（RNST）已被证明可以在许多语音识别任务上提供最先进的性能，因为它们能够提供学习的所有序列历史的动态变化的上下文窗口。另一方面，卷积神经网络（CNN）为深度前馈神经网络（FFNN）带来了显着的改进，因为它们能够更好地减少输入信号中的频谱变化。本文将CNN和LSTM RNN相结合，提出了卷积递归神经网络（CRNN）的网络结构。在所提出的CRNN中，没有相邻上下文帧的每个语音帧被组织为沿着频率轴的多个局部特征块，然后沿着时间轴对每个特征块执行LSTM网络。我们训练和比较FFNN，LSTM RNN和建议的LSTM CRNN在各种配置。实验结果表明，LSTM CRNN可以超越最先进的语音识别性能。

##### URL
[https://arxiv.org/abs/1610.03165](https://arxiv.org/abs/1610.03165)

##### PDF
[https://arxiv.org/pdf/1610.03165](https://arxiv.org/pdf/1610.03165)

