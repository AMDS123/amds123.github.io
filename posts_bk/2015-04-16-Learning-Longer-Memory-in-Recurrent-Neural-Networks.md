---
layout: post
title: "Learning Longer Memory in Recurrent Neural Networks"
date: 2015-04-16 23:37:58
categories: arXiv_CV
tags: arXiv_CV RNN Language_Model Gradient_Descent
author: Tomas Mikolov, Armand Joulin, Sumit Chopra, Michael Mathieu, Marc'Aurelio Ranzato
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural network is a powerful model that learns temporal patterns in sequential data. For a long time, it was believed that recurrent networks are difficult to train using simple optimizers, such as stochastic gradient descent, due to the so-called vanishing gradient problem. In this paper, we show that learning longer term patterns in real data, such as in natural language, is perfectly possible using gradient descent. This is achieved by using a slight structural modification of the simple recurrent neural network architecture. We encourage some of the hidden units to change their state slowly by making part of the recurrent weight matrix close to identity, thus forming kind of a longer term memory. We evaluate our model in language modeling experiments, where we obtain similar performance to the much more complex Long Short Term Memory (LSTM) networks (Hochreiter & Schmidhuber, 1997).

##### Abstract (translated by Google)
递归神经网络是学习顺序数据中的时间模式的强大模型。长期以来，人们认为由于所谓的消失梯度问题，经常性网络难以使用简单的优化器进行训练，例如随机梯度下降。在本文中，我们表明，学习长期模式在真实的数据，如自然语言，是完全有可能使用梯度下降。这是通过使用简单的递归神经网络架构的轻微的结构修改来实现的。我们鼓励一些隐藏的单位通过使接近于身份的经常权重矩阵的一部分缓慢地改变他们的状态，从而形成一种长期记忆。我们在语言建模实验中评估我们的模型，在那里我们获得与更复杂的长期短期记忆（LSTM）网络（Hochreiter＆Schmidhuber，1997）相似的性能。

##### URL
[https://arxiv.org/abs/1412.7753](https://arxiv.org/abs/1412.7753)

##### PDF
[https://arxiv.org/pdf/1412.7753](https://arxiv.org/pdf/1412.7753)

