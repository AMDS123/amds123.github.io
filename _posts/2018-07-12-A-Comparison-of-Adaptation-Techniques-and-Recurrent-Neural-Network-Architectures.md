---
layout: post
title: "A Comparison of Adaptation Techniques and Recurrent Neural Network Architectures"
date: 2018-07-12 09:40:21
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition RNN Language_Model Recognition
author: Jan Vanek, Josef Michalek, Jan Zelinka, Josef Psutka
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, recurrent neural networks have become state-of-the-art in acoustic modeling for automatic speech recognition. The long short-term memory (LSTM) units are the most popular ones. However, alternative units like gated recurrent unit (GRU) and its modifications outperformed LSTM in some publications. In this paper, we compared five neural network (NN) architectures with various adaptation and feature normalization techniques. We have evaluated feature-space maximum likelihood linear regression, five variants of i-vector adaptation and two variants of cepstral mean normalization. The most adaptation and normalization techniques were developed for feed-forward NNs and, according to results in this paper, not all of them worked also with RNNs. For experiments, we have chosen a well known and available TIMIT phone recognition task. The phone recognition is much more sensitive to the quality of AM than large vocabulary task with a complex language model. Also, we published the open-source scripts to easily replicate the results and to help continue the development.

##### Abstract (translated by Google)
最近，递归神经网络已成为用于自动语音识别的声学建模的最新技术。长短期记忆（LSTM）单位是最受欢迎的单位。然而，在一些出版物中，诸如门控循环单元（GRU）及其修改的替代单元优于LSTM。在本文中，我们比较了五种神经网络（NN）架构与各种适应和特征归一化技术。我们已经评估了特征空间最大似然线性回归，i-向量适应的五种变体和倒谱平均归一化的两种变体。最适应和标准化技术是针对前馈NN而开发的，根据本文的结果，并非所有技术都适用于RNN。对于实验，我们选择了一个众所周知且可用的TIMIT电话识别任务。与具有复杂语言模型的大词汇量任务相比，电话识别对AM的质量更敏感。此外，我们发布了开源脚本，以便轻松复制结果并帮助继续开发。

##### URL
[http://arxiv.org/abs/1807.06441](http://arxiv.org/abs/1807.06441)

##### PDF
[http://arxiv.org/pdf/1807.06441](http://arxiv.org/pdf/1807.06441)

