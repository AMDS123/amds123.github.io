---
layout: post
title: "A Simple LSTM model for Transition-based Dependency Parsing"
date: 2017-09-08 22:46:59
categories: arXiv_CL
tags: arXiv_CL RNN
author: Mohab Elkaref, Bernd Bohnet
mathjax: true
---

* content
{:toc}

##### Abstract
We present a simple LSTM-based transition-based dependency parser. Our model is composed of a single LSTM hidden layer replacing the hidden layer in the usual feed-forward network architecture. We also propose a new initialization method that uses the pre-trained weights from a feed-forward neural network to initialize our LSTM-based model. We also show that using dropout on the input layer has a positive effect on performance. Our final parser achieves a 93.06% unlabeled and 91.01% labeled attachment score on the Penn Treebank. We additionally replace LSTMs with GRUs and Elman units in our model and explore the effectiveness of our initialization method on individual gates constituting all three types of RNN units.

##### Abstract (translated by Google)
我们提出一个简单的基于LSTM的基于转换的依赖关系解析器。我们的模型由一个单独的LSTM隐藏层组成，代替了通常的前馈网络架构中的隐藏层。我们还提出了一种新的初始化方法，使用来自前馈神经网络的预先训练的权重来初始化基于LSTM的模型。我们还表明，在输入层使用dropout对性能有积极的影响。我们的最终解析器在Penn Treebank上实现了93.06％的未标记和91.01％的标记附着分数。我们另外用我们的模型中的GRU和Elman单元代替LSTM，并探索初始化方法在构成所有三种RNN单元的各个门上的有效性。

##### URL
[https://arxiv.org/abs/1708.08959](https://arxiv.org/abs/1708.08959)

##### PDF
[https://arxiv.org/pdf/1708.08959](https://arxiv.org/pdf/1708.08959)

