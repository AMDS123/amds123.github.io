---
layout: post
title: "Quasi-Recurrent Neural Networks"
date: 2016-11-21 20:52:34
categories: arXiv_CL
tags: arXiv_CL Sentiment Sentiment_Classification CNN RNN Classification Language_Model
author: James Bradbury, Stephen Merity, Caiming Xiong, Richard Socher
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks are a powerful tool for modeling sequential data, but the dependence of each timestep's computation on the previous timestep's output limits parallelism and makes RNNs unwieldy for very long sequences. We introduce quasi-recurrent neural networks (QRNNs), an approach to neural sequence modeling that alternates convolutional layers, which apply in parallel across timesteps, and a minimalist recurrent pooling function that applies in parallel across channels. Despite lacking trainable recurrent layers, stacked QRNNs have better predictive accuracy than stacked LSTMs of the same hidden size. Due to their increased parallelism, they are up to 16 times faster at train and test time. Experiments on language modeling, sentiment classification, and character-level neural machine translation demonstrate these advantages and underline the viability of QRNNs as a basic building block for a variety of sequence tasks.

##### Abstract (translated by Google)
递归神经网络是时序数据建模的强大工具，但是每个时步计算对前一时刻的输出的依赖限制了并行性，并且使得RNN在很长的序列中难以使用。我们引入了准递归神经网络（quasi-recurrentneuralnetwork，QRNN），这是一种交替使用卷积层的神经序列建模方法，跨时间步并行应用，并且跨频道并行应用最小复发池功能。尽管缺少可训练的复发层，堆叠的QRNN比具有相同隐藏大小的堆叠LSTM具有更好的预测准确性。由于它们的并行性增加，在火车和测试时间，速度提高了16倍。在语言建模，情感分类和字符级神经机器翻译方面的实验证明了这些优点，并且强调了QRNNs作为各种序列任务的基本构建块的可行性。

##### URL
[https://arxiv.org/abs/1611.01576](https://arxiv.org/abs/1611.01576)

##### PDF
[https://arxiv.org/pdf/1611.01576](https://arxiv.org/pdf/1611.01576)

