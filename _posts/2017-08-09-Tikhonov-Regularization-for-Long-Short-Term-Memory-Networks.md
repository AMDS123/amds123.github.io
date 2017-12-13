---
layout: post
title: "Tikhonov Regularization for Long Short-Term Memory Networks"
date: 2017-08-09 19:34:26
categories: arXiv_CV
tags: arXiv_CV Regularization RNN Memory_Networks
author: Andrei Turkin
mathjax: true
---

* content
{:toc}

##### Abstract
It is a well-known fact that adding noise to the input data often improves network performance. While the dropout technique may be a cause of memory loss, when it is applied to recurrent connections, Tikhonov regularization, which can be regarded as the training with additive noise, avoids this issue naturally, though it implies regularizer derivation for different architectures. In case of feedforward neural networks this is straightforward, while for networks with recurrent connections and complicated layers it leads to some difficulties. In this paper, a Tikhonov regularizer is derived for Long-Short Term Memory (LSTM) networks. Although it is independent of time for simplicity, it considers interaction between weights of the LSTM unit, which in theory makes it possible to regularize the unit with complicated dependences by using only one parameter that measures the input data perturbation. The regularizer that is proposed in this paper has three parameters: one to control the regularization process, and other two to maintain computation stability while the network is being trained. The theory developed in this paper can be applied to get such regularizers for different recurrent neural networks with Hadamard products and Lipschitz continuous functions.

##### Abstract (translated by Google)
众所周知的事实是，向输入数据添加噪声通常会提高网络性能。虽然丢失技术可能是记忆丢失的一个原因，但是当将其应用于经常性连接时，可以将其看作具有加性噪声的训练的Tikhonov正则化自然地避免了这个问题，尽管这意味着不同体系结构的正则化器推导。在前馈神经网络的情况下，这是简单的，而对于具有复杂连接和复杂层次的网络，则会导致一些困难。在本文中，一个Tikhonov调节器是由长 - 短期记忆（LSTM）网络推导出来的。尽管简单性与时间无关，但它考虑了LSTM单元的权重之间的相互作用，理论上它可以通过仅使用测量输入数据扰动的一个参数来使具有复杂相关性的单元正规化。本文提出的正则化器有三个参数：一个用于控制正则化过程，另外两个用于维持网络训练时的计算稳定性。本文提出的理论可以应用于Hadamard积和Lipschitz连续函数的不同递归神经网络的正则化。

##### URL
[https://arxiv.org/abs/1708.02979](https://arxiv.org/abs/1708.02979)

##### PDF
[https://arxiv.org/pdf/1708.02979](https://arxiv.org/pdf/1708.02979)

