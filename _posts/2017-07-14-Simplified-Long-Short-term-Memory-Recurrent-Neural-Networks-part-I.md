---
layout: post
title: "Simplified Long Short-term Memory Recurrent Neural Networks: part I"
date: 2017-07-14 19:46:59
categories: arXiv_CV
tags: arXiv_CV RNN
author: Atra Akandeh, Fathi M. Salem
mathjax: true
---

* content
{:toc}

##### Abstract
We present five variants of the standard Long Short-term Memory (LSTM) recurrent neural networks by uniformly reducing blocks of adaptive parameters in the gating mechanisms. For simplicity, we refer to these models as LSTM1, LSTM2, LSTM3, LSTM4, and LSTM5, respectively. Such parameter-reduced variants enable speeding up data training computations and would be more suitable for implementations onto constrained embedded platforms. We comparatively evaluate and verify our five variant models on the classical MNIST dataset and demonstrate that these variant models are comparable to a standard implementation of the LSTM model while using less number of parameters. Moreover, we observe that in some cases the standard LSTM's accuracy performance will drop after a number of epochs when using the ReLU nonlinearity; in contrast, however, LSTM3, LSTM4 and LSTM5 will retain their performance.

##### Abstract (translated by Google)
通过在门控机制中统一减少自适应参数块，我们提出了标准的长期短期记忆（LSTM）递归神经网络的五种变体。为简单起见，我们将这些模型分别称为LSTM1，LSTM2，LSTM3，LSTM4和LSTM5。这种参数减少的变体可以加快数据训练计算速度，并且更适合在受限制的嵌入式平台上实现。我们在经典的MNIST数据集上比较评估和验证我们的五个变体模型，并证明这些变体模型与使用较少参数的LSTM模型的标准实现相当。此外，我们观察到，在某些情况下，使用ReLU非线性时，标准LSTM的精度性能会在若干个时代后下降;相比之下，LSTM3，LSTM4和LSTM5将保持其表现。

##### URL
[https://arxiv.org/abs/1707.04619](https://arxiv.org/abs/1707.04619)

##### PDF
[https://arxiv.org/pdf/1707.04619](https://arxiv.org/pdf/1707.04619)

