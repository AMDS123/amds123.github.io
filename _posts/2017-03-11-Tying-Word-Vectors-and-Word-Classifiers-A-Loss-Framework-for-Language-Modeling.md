---
layout: post
title: "Tying Word Vectors and Word Classifiers: A Loss Framework for Language Modeling"
date: 2017-03-11 19:13:52
categories: arXiv_CL
tags: arXiv_CL Embedding RNN Classification Language_Model
author: Hakan Inan, Khashayar Khosravi, Richard Socher
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks have been very successful at predicting sequences of words in tasks such as language modeling. However, all such models are based on the conventional classification framework, where the model is trained against one-hot targets, and each word is represented both as an input and as an output in isolation. This causes inefficiencies in learning both in terms of utilizing all of the information and in terms of the number of parameters needed to train. We introduce a novel theoretical framework that facilitates better learning in language modeling, and show that our framework leads to tying together the input embedding and the output projection matrices, greatly reducing the number of trainable variables. Our framework leads to state of the art performance on the Penn Treebank with a variety of network models.

##### Abstract (translated by Google)
递归神经网络在预测诸如语言建模等任务中的字词序列方面已经非常成功。然而，所有这些模型都是基于传统的分类框架，模型是针对一个热门的目标进行训练的，每个词都被单独表示为输入和输出。这导致在利用所有信息方面以及在训练所需的参数数量方面的低效率。我们引入了一个新颖的理论框架来促进语言建模中的更好的学习，并且表明我们的框架导致将输入嵌入和输出投影矩阵联系在一起，大大减少了可训练变量的数量。我们的框架通过各种网络模型导致Penn Treebank的最新性能表现。

##### URL
[https://arxiv.org/abs/1611.01462](https://arxiv.org/abs/1611.01462)

##### PDF
[https://arxiv.org/pdf/1611.01462](https://arxiv.org/pdf/1611.01462)

