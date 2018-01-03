---
layout: post
title: "Character-level Recurrent Neural Networks in Practice: Comparing Training and Sampling Schemes"
date: 2018-01-02 12:50:12
categories: arXiv_CL
tags: arXiv_CL RNN Deep_Learning Recommendation
author: Cedric De Boom, Bart Dhoedt, Thomas Demeester
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks are nowadays successfully used in an abundance of applications, going from text, speech and image processing to recommender systems. Backpropagation through time is the algorithm that is commonly used to train these networks on specific tasks. Many deep learning frameworks have their own implementation of training and sampling procedures for recurrent neural networks, while there are in fact multiple other possibilities to choose from and other parameters to tune. In existing literature this is very often overlooked or ignored. In this paper we therefore give an overview of possible training and sampling schemes for character-level recurrent neural networks to solve the task of predicting the next token in a given sequence. We test these different schemes on a variety of datasets, neural network architectures and parameter settings, and formulate a number of take-home recommendations. The choice of training and sampling scheme turns out to be subject to a number of trade-offs, such as training stability, sampling time, model performance and implementation effort, but is largely independent of the data. Perhaps the most surprising result is that transferring hidden states for correctly initializing the model on subsequences often leads to unstable training behavior depending on the dataset.

##### Abstract (translated by Google)
递归神经网络现在已经成功地用于大量的应用，从文本，语音和图像处理到推荐系统。通过时间反向传播是通常用于在特定任务上训练这些网络的算法。许多深度学习框架都有自己的循环神经网络训练和抽样程序的实现，而实际上有多种其他的可能性可供选择和调整其他参数。在现有的文献中，这经常被忽视或忽略。因此，在本文中，我们将概述可能的训练和采样方案的字符级递归神经网络，以解决在给定序列中预测下一个令牌的任务。我们在各种数据集，神经网络体系结构和参数设置上测试了这些不同的方案，并制定了一些实施建议。训练和抽样方案的选择结果受到一些权衡，如训练稳定性，抽样时间，模型性能和实施努力，但在很大程度上独立于数据。也许最令人惊讶的结果是，转移隐藏状态以正确初始化子序列上的模型常常导致取决于数据集的不稳定的训练行为。

##### URL
[http://arxiv.org/abs/1801.00632](http://arxiv.org/abs/1801.00632)

##### PDF
[http://arxiv.org/pdf/1801.00632](http://arxiv.org/pdf/1801.00632)

