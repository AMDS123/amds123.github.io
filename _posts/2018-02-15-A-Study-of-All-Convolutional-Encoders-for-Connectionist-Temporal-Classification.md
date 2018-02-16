---
layout: post
title: "A Study of All-Convolutional Encoders for Connectionist Temporal Classification"
date: 2018-02-15 18:55:30
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition CNN RNN Classification Prediction Recognition
author: Kalpesh Krishna, Liang Lu, Kevin Gimpel, Karen Livescu
mathjax: true
---

* content
{:toc}

##### Abstract
Connectionist temporal classification (CTC) is a popular sequence prediction approach for automatic speech recognition that is typically used with models based on recurrent neural networks (RNNs). We explore whether deep convolutional neural networks (CNNs) can be used effectively instead of RNNs as the "encoder" in CTC. CNNs lack an explicit representation of the entire sequence, but have the advantage that they are much faster to train. We present an exploration of CNNs as encoders for CTC models, in the context of character-based (lexicon-free) automatic speech recognition. In particular, we explore a range of one-dimensional convolutional layers, which are particularly efficient. We compare the performance of our CNN-based models against typical RNNbased models in terms of training time, decoding time, model size and word error rate (WER) on the Switchboard Eval2000 corpus. We find that our CNN-based models are close in performance to LSTMs, while not matching them, and are much faster to train and decode.

##### Abstract (translated by Google)
Connectionist时间分类（CTC）是用于自动语音识别的流行序列预测方法，其通常与基于递归神经网络（RNN）的模型一起使用。我们研究深层卷积神经网络（CNNs）是否可以有效地用作CTC中的“编码器”，而不是RNNs。 CNN缺乏整个序列的明确表示，但具有训练速度更快的优点。在基于字符（无词典）自动语音识别的背景下，我们将CNN作为CTC模型的编码器进行探索。特别是，我们探索了一系列一维卷积层，其效率特别高。在Switchboard Eval2000语料库中，我们比较了基于CNN的模型与典型的基于RNN的模型在训练时间，解码时间，模型大小和字错误率（WER）方面的性能。我们发现我们的基于CNN的模型在性能上与LSTM接近，但与它们不匹配，并且训练和解码要快得多。

##### URL
[http://arxiv.org/abs/1710.10398](http://arxiv.org/abs/1710.10398)

##### PDF
[http://arxiv.org/pdf/1710.10398](http://arxiv.org/pdf/1710.10398)

