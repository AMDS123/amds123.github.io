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


##### URL
[https://arxiv.org/abs/1412.7753](https://arxiv.org/abs/1412.7753)

##### PDF
[https://arxiv.org/pdf/1412.7753](https://arxiv.org/pdf/1412.7753)

