---
layout: post
title: "A Seq-to-Seq Transformer Premised Temporal Convolutional Network for Chinese Word Segmentation"
date: 2019-05-21 06:12:47
categories: arXiv_CL
tags: arXiv_CL Segmentation CNN RNN
author: Wei Jiang, Yan Tang
mathjax: true
---

* content
{:toc}

##### Abstract
The prevalent approaches of Chinese word segmentation task almost rely on the Bi-LSTM neural network. However, the methods based the Bi-LSTM have some inherent drawbacks: hard to parallel computing, little efficient in applying the Dropout method to inhibit the Overfitting and little efficient in capturing the character information at the more distant site of a long sentence for the word segmentation task. In this work, we propose a sequence-to-sequence transformer model for Chinese word segmentation, which is premised a type of convolutional neural network named temporal convolutional network. The model uses the temporal convolutional network to construct an encoder, and uses one layer of fully-connected neural network to build a decoder, and applies the Dropout method to inhibit the Overfitting, and captures the character information at the distant site of a sentence by adding the layers of the encoder, and binds Conditional Random Fields model to train parameters, and uses the Viterbi algorithm to infer the final result of the Chinese word segmentation. The experiments on traditional Chinese corpora and simplified Chinese corpora show that the performance of Chinese word segmentation of the model is equivalent to the performance of the methods based the Bi-LSTM, and the model has a tremendous growth in parallel computing than the models based the Bi-LSTM.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.08454](http://arxiv.org/abs/1905.08454)

##### PDF
[http://arxiv.org/pdf/1905.08454](http://arxiv.org/pdf/1905.08454)

