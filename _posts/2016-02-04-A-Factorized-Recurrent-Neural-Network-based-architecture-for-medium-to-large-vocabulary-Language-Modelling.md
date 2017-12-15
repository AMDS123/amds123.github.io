---
layout: post
title: "A Factorized Recurrent Neural Network based architecture for medium to large vocabulary Language Modelling"
date: 2016-02-04 07:53:11
categories: arXiv_SD
tags: arXiv_SD RNN Language_Model Prediction
author: Anantharaman Palacode Narayana Iyer
mathjax: true
---

* content
{:toc}

##### Abstract
Statistical language models are central to many applications that use semantics. Recurrent Neural Networks (RNN) are known to produce state of the art results for language modelling, outperforming their traditional n-gram counterparts in many cases. To generate a probability distribution across a vocabulary, these models require a softmax output layer that linearly increases in size with the size of the vocabulary. Large vocabularies need a commensurately large softmax layer and training them on typical laptops/PCs requires significant time and machine resources. In this paper we present a new technique for implementing RNN based large vocabulary language models that substantially speeds up computation while optimally using the limited memory resources. Our technique, while building on the notion of factorizing the output layer by having multiple output layers, improves on the earlier work by substantially optimizing on the individual output layer size and also eliminating the need for a multistep prediction process.

##### Abstract (translated by Google)
统计语言模型是许多使用语义的应用程序的核心。已知递归神经网络（RNN）在语言建模方面产生最先进的结果，在许多情况下，其性能优于传统的n-gram。为了在词汇表中产生一个概率分布，这些模型需要一个softmax输出层，它随着词汇的大小线性增加。大型词汇表需要相当大的softmax层，并且在典型的笔记本电脑/ PC上进行培训需要大量的时间和机器资源。在本文中，我们提出了一种实现基于RNN的大型词汇语言模型的新技术，该技术大大加快了计算速度，同时优化使用有限的存储资源。我们的技术在建立在具有多个输出层的输出层因式分解概念的基础上，通过对各个输出层大小进行实质优化并且不再需要多步预测过程而改进了早期的工作。

##### URL
[https://arxiv.org/abs/1602.01576](https://arxiv.org/abs/1602.01576)

##### PDF
[https://arxiv.org/pdf/1602.01576](https://arxiv.org/pdf/1602.01576)

