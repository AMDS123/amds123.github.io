---
layout: post
title: "Dual Rectified Linear Units : A Replacement for Tanh Activation Functions in Quasi-Recurrent Neural Networks"
date: 2017-10-31 15:50:57
categories: arXiv_CL
tags: arXiv_CL Sentiment Sparse Sentiment_Classification RNN Classification Language_Model Memory_Networks
author: Fréderic Godin, Jonas Degrave, Joni Dambre, Wesley De Neve
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce a novel type of Rectified Linear Unit (ReLU), called a Dual Rectified Linear Unit (DReLU). A DReLU, which comes with an unbounded positive and negative image, can be used as a drop-in replacement for a tanh activation function in the recurrent step of Quasi-Recurrent Neural Networks (QRNNs) (Bradbury et al. (2017)). Similar to ReLUs, DReLUs are less prone to the vanishing gradient problem, they are noise robust, and they induce sparse activations. We independently reproduce the QRNN experiments of Bradbury et al. (2017) and compare our DReLU-based QRNNs with the original tanh-based QRNNs and Long Short-Term Memory networks (LSTMs) on sentiment classification and word-level language modeling. Additionally, we evaluate on character-level language modeling, showing that we are able to stack up to eight QRNN layers with DReLUs, thus making it possible to improve the current state-of-the-art in character-level language modeling over shallow architectures based on LSTMs.

##### Abstract (translated by Google)
在本文中，我们介绍一种新型的整流线性单元（ReLU），称为双整流线性单元（DReLU）。带有无限正负图像的DReLU可以用作准递归神经网络（QRNNs）（Bradbury等（2017））的递归步骤中的tanh激活函数的直接替换。与ReLU类似，DReLU不易陷入消失梯度问题，它们具有鲁棒性，并且引发稀疏激活。我们独立重现了Bradbury等人的QRNN实验。 （2017），并将我们的基于DReLU的QRNN与基于tanh的QRNN和长期短期记忆网络（LSTM）进行情感分类和词级语言建模的比较。此外，我们对字符级语言建模进行了评估，表明我们能够使用DReLU堆叠多达8个QRNN图层，从而可以改进浅层架构上字符级语言建模的当前最新技术水平基于LSTMs。

##### URL
[https://arxiv.org/abs/1707.08214](https://arxiv.org/abs/1707.08214)

##### PDF
[https://arxiv.org/pdf/1707.08214](https://arxiv.org/pdf/1707.08214)

