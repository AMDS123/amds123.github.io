---
layout: post
title: "Long Short-Term Memory as a Dynamically Computed Element-wise Weighted Sum"
date: 2018-05-09 20:05:58
categories: arXiv_AI
tags: arXiv_AI RNN
author: Omer Levy, Kenton Lee, Nicholas FitzGerald, Luke Zettlemoyer
mathjax: true
---

* content
{:toc}

##### Abstract
LSTMs were introduced to combat vanishing gradients in simple RNNs by augmenting them with gated additive recurrent connections. We present an alternative view to explain the success of LSTMs: the gates themselves are versatile recurrent models that provide more representational power than previously appreciated. We do this by decoupling the LSTM's gates from the embedded simple RNN, producing a new class of RNNs where the recurrence computes an element-wise weighted sum of context-independent functions of the input. Ablations on a range of problems demonstrate that the gating mechanism alone performs as well as an LSTM in most settings, strongly suggesting that the gates are doing much more in practice than just alleviating vanishing gradients.

##### Abstract (translated by Google)
引入LSTM是为了克服简单RNN中的消失梯度，通过增加门控加性循环连接来增强梯度。我们提出了另一种解释LSTMs成功的观点：门本身是多功能的经常性模型，提供比先前所赞赏的更多的表现力。我们通过将LSTM的门与嵌入式简单RNN解耦，从而产生一类新的RNN，其中递归计算输入的与上下文无关的函数的元素加权和。一系列问题的消除表明，门控机制在大多数环境中的表现都与LSTM一样好，这表明门在实践中的作用远远超过缓解渐变渐变。

##### URL
[http://arxiv.org/abs/1805.03716](http://arxiv.org/abs/1805.03716)

##### PDF
[http://arxiv.org/pdf/1805.03716](http://arxiv.org/pdf/1805.03716)

