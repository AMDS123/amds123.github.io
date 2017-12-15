---
layout: post
title: "Regularizing RNNs by Stabilizing Activations"
date: 2016-04-26 05:21:11
categories: arXiv_CL
tags: arXiv_CL RNN Language_Model Recognition
author: David Krueger, Roland Memisevic
mathjax: true
---

* content
{:toc}

##### Abstract
We stabilize the activations of Recurrent Neural Networks (RNNs) by penalizing the squared distance between successive hidden states' norms. This penalty term is an effective regularizer for RNNs including LSTMs and IRNNs, improving performance on character-level language modeling and phoneme recognition, and outperforming weight noise and dropout. We achieve competitive performance (18.6\% PER) on the TIMIT phoneme recognition task for RNNs evaluated without beam search or an RNN transducer. With this penalty term, IRNN can achieve similar performance to LSTM on language modeling, although adding the penalty term to the LSTM results in superior performance. Our penalty term also prevents the exponential growth of IRNN's activations outside of their training horizon, allowing them to generalize to much longer sequences.

##### Abstract (translated by Google)
我们通过惩罚连续隐藏状态的规范之间的平方距离来稳定递归神经网络（RNN）的激活。这个惩罚术语对于包括LSTM和IRNN的RNN来说是一个有效的正规化器，提高了字符级语言建模和音素识别的性能，并且优于重量噪声和丢失。我们在没有波束搜索或RNN传感器的情况下对RNN的TIMIT音素识别任务实现了有竞争力的表现（18.6％PER）。有了这个惩罚术语，IRNN可以在语言建模方面达到与LSTM类似的性能，但是向LSTM添加惩罚项会获得更好的性能。我们的惩罚期也阻止了IRNN在训练范围之外激活的指数增长，使得它们能够推广到更长的序列。

##### URL
[https://arxiv.org/abs/1511.08400](https://arxiv.org/abs/1511.08400)

##### PDF
[https://arxiv.org/pdf/1511.08400](https://arxiv.org/pdf/1511.08400)

