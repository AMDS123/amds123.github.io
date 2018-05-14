---
layout: post
title: "State Gradients for RNN Memory Analysis"
date: 2018-05-11 07:51:28
categories: arXiv_CL
tags: arXiv_CL Embedding RNN Language_Model Relation
author: Lyan Verwimp, Hugo Van hamme, Vincent Renkens, Patrick Wambacq
mathjax: true
---

* content
{:toc}

##### Abstract
We present a framework for analyzing what the state in RNNs remembers from its input embeddings. Our approach is inspired by backpropagation, in the sense that we compute the gradients of the states with respect to the input embeddings. The gradient matrix is decomposed with Singular Value Decomposition to analyze which directions in the embedding space are best transferred to the hidden state space, characterized by the largest singular values. We apply our approach to LSTM language models and investigate to what extent and for how long certain classes of words are remembered on average for a certain corpus. Additionally, the extent to which a specific property or relationship is remembered by the RNN can be tracked by comparing a vector characterizing that property with the direction(s) in embedding space that are best preserved in hidden state space.

##### Abstract (translated by Google)
我们提出了一个分析RNN中的状态从其输入嵌入中记录的内容的框架。我们的方法受到反向传播的启发，因为我们根据输入嵌入来计算状态的梯度。利用奇异值分解对梯度矩阵进行分解，以分析嵌入空间中哪些方向最好转移到以最大奇异值为特征的隐藏状态空间。我们将我们的方法应用于LSTM语言模型，并调查特定语料库平均记住某些类别的词汇的程度和时间。另外，通过将表征该属性的矢量与在隐藏状态空间中最好地保存的嵌入空间中的方向进行比较，可以追踪RNN记住特定属性或关系的程度。

##### URL
[http://arxiv.org/abs/1805.04264](http://arxiv.org/abs/1805.04264)

##### PDF
[http://arxiv.org/pdf/1805.04264](http://arxiv.org/pdf/1805.04264)

