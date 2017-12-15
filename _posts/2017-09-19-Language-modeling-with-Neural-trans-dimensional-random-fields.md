---
layout: post
title: "Language modeling with Neural trans-dimensional random fields"
date: 2017-09-19 08:28:42
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Embedding CNN Inference RNN Language_Model Recognition
author: Bin Wang, Zhijian Ou
mathjax: true
---

* content
{:toc}

##### Abstract
Trans-dimensional random field language models (TRF LMs) have recently been introduced, where sentences are modeled as a collection of random fields. The TRF approach has been shown to have the advantages of being computationally more efficient in inference than LSTM LMs with close performance and being able to flexibly integrating rich features. In this paper we propose neural TRFs, beyond of the previous discrete TRFs that only use linear potentials with discrete features. The idea is to use nonlinear potentials with continuous features, implemented by neural networks (NNs), in the TRF framework. Neural TRFs combine the advantages of both NNs and TRFs. The benefits of word embedding, nonlinear feature learning and larger context modeling are inherited from the use of NNs. At the same time, the strength of efficient inference by avoiding expensive softmax is preserved. A number of technical contributions, including employing deep convolutional neural networks (CNNs) to define the potentials and incorporating the joint stochastic approximation (JSA) strategy in the training algorithm, are developed in this work, which enable us to successfully train neural TRF LMs. Various LMs are evaluated in terms of speech recognition WERs by rescoring the 1000-best lists of WSJ'92 test data. The results show that neural TRF LMs not only improve over discrete TRF LMs, but also perform slightly better than LSTM LMs with only one fifth of parameters and 16x faster inference efficiency.

##### Abstract (translated by Google)
最近已经引入了跨维随机场语言模型（TRF LM），其中句子被建模为随机场的集合。已经证明TRF方法比具有接近性能的LSTM LM具有在计算上更有效的推断的优点，并且能够灵活地整合丰富的特征。在本文中，我们提出神经TRF，超越以前的离散TRF，只使用具有离散特征的线性电位。这个想法是在TRF框架中使用由神经网络（NNs）实现的具有连续特征的非线性势能。神经TRF结合了NN和TRF的优点。词嵌入，非线性特征学习和更大的上下文建模的好处是从NN的使用继承。同时，避免了昂贵的softmax的有效推理的强度被保留下来。本文开发了一些技术贡献，包括利用深度卷积神经网络（CNNs）来定义潜能，并将联合随机近似（JSA）策略引入训练算法，使我们能够成功地训练神经TRF LMs。通过对WSJ'92测试数据的1000个最佳列表进行重新评估，各种LM被评估为语音识别WER。结果表明，神经TRF LM不仅比单独的TRF LM改善，而且比LSTM LM略好，只有五分之一的参数和16倍的推理效率。

##### URL
[https://arxiv.org/abs/1707.07240](https://arxiv.org/abs/1707.07240)

##### PDF
[https://arxiv.org/pdf/1707.07240](https://arxiv.org/pdf/1707.07240)

