---
layout: post
title: "Convolutional Sequence to Sequence Learning"
date: 2017-07-25 01:40:57
categories: arXiv_CL
tags: arXiv_CL Attention CNN Optimization RNN
author: Jonas Gehring, Michael Auli, David Grangier, Denis Yarats, Yann N. Dauphin
mathjax: true
---

* content
{:toc}

##### Abstract
The prevalent approach to sequence to sequence learning maps an input sequence to a variable length output sequence via recurrent neural networks. We introduce an architecture based entirely on convolutional neural networks. Compared to recurrent models, computations over all elements can be fully parallelized during training and optimization is easier since the number of non-linearities is fixed and independent of the input length. Our use of gated linear units eases gradient propagation and we equip each decoder layer with a separate attention module. We outperform the accuracy of the deep LSTM setup of Wu et al. (2016) on both WMT'14 English-German and WMT'14 English-French translation at an order of magnitude faster speed, both on GPU and CPU.

##### Abstract (translated by Google)
对序列学习进行排序的流行方法通过递归神经网络将输入序列映射到变长输出序列。我们介绍完全基于卷积神经网络的架构。与循环模型相比，所有元素的计算可以在训练期间完全并行化，并且由于非线性的数量是固定的并且与输入长度无关，所以优化更容易。我们使用门控线性单元减轻了梯度传播，并为每个解码器层配备了一个单独的注意模块。我们超越了Wu等人的深层LSTM设置的准确性。 （2016）对WMT'14英德语和WMT'14英语 - 法语翻译的速度提高了一个数量级，GPU和CPU。

##### URL
[https://arxiv.org/abs/1705.03122](https://arxiv.org/abs/1705.03122)

##### PDF
[https://arxiv.org/pdf/1705.03122](https://arxiv.org/pdf/1705.03122)

