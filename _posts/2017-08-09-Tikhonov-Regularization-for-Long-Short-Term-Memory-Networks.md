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


##### URL
[https://arxiv.org/abs/1708.02979](https://arxiv.org/abs/1708.02979)

##### PDF
[https://arxiv.org/pdf/1708.02979](https://arxiv.org/pdf/1708.02979)

