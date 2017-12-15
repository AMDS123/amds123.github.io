---
layout: post
title: "Exponential Moving Average Model in Parallel Speech Recognition Training"
date: 2017-03-03 03:14:28
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition RNN Recognition
author: Xu Tian, Jun Zhang, Zejun Ma, Yi He, Juan Wei
mathjax: true
---

* content
{:toc}

##### Abstract
As training data rapid growth, large-scale parallel training with multi-GPUs cluster is widely applied in the neural network model learning currently.We present a new approach that applies exponential moving average method in large-scale parallel training of neural network model. It is a non-interference strategy that the exponential moving average model is not broadcasted to distributed workers to update their local models after model synchronization in the training process, and it is implemented as the final model of the training system. Fully-connected feed-forward neural networks (DNNs) and deep unidirectional Long short-term memory (LSTM) recurrent neural networks (RNNs) are successfully trained with proposed method for large vocabulary continuous speech recognition on Shenma voice search data in Mandarin. The character error rate (CER) of Mandarin speech recognition further degrades than state-of-the-art approaches of parallel training.

##### Abstract (translated by Google)
随着训练数据的快速增长，目前大规模的多GPU集群并行训练在神经网络模型学习中得到了广泛的应用。本文提出了一种将指数滑动平均法应用于神经网络模型大规模并行训练的新方法。在训练过程中模型同步后，指数移动平均模型不再广播给分布式工作人员更新其局部模型，而是作为训练系统的最终模型实施。在神马语音搜索数据的基础上，提出了大连词语连续语音识别的全连接前馈神经网络（DNNs）和深度单向长时间短语记忆（LSTM）递归神经网络（RNNs）。普通话语音识别的字符错误率（CER）比平行训练的最新方法进一步降低。

##### URL
[https://arxiv.org/abs/1703.01024](https://arxiv.org/abs/1703.01024)

##### PDF
[https://arxiv.org/pdf/1703.01024](https://arxiv.org/pdf/1703.01024)

