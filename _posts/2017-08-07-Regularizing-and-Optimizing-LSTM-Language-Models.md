---
layout: post
title: "Regularizing and Optimizing LSTM Language Models"
date: 2017-08-07 16:03:44
categories: arXiv_CL
tags: arXiv_CL Regularization RNN Language_Model Memory_Networks
author: Stephen Merity, Nitish Shirish Keskar, Richard Socher
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks (RNNs), such as long short-term memory networks (LSTMs), serve as a fundamental building block for many sequence learning tasks, including machine translation, language modeling, and question answering. In this paper, we consider the specific problem of word-level language modeling and investigate strategies for regularizing and optimizing LSTM-based models. We propose the weight-dropped LSTM which uses DropConnect on hidden-to-hidden weights as a form of recurrent regularization. Further, we introduce NT-ASGD, a variant of the averaged stochastic gradient method, wherein the averaging trigger is determined using a non-monotonic condition as opposed to being tuned by the user. Using these and other regularization strategies, we achieve state-of-the-art word level perplexities on two data sets: 57.3 on Penn Treebank and 65.8 on WikiText-2. In exploring the effectiveness of a neural cache in conjunction with our proposed model, we achieve an even lower state-of-the-art perplexity of 52.8 on Penn Treebank and 52.0 on WikiText-2.

##### Abstract (translated by Google)
递归神经网络（RNN），如长期短期记忆网络（LSTM），可作为许多序列学习任务（包括机器翻译，语言建模和问答）的基本构建模块。在本文中，我们考虑了字级语言建模的具体问题，并研究了基于LSTM的模型的正则化和优化策略。我们提出了使用DropConnect作为一种反复正则化形式的权重下降LSTM在隐藏到隐藏的权重。此外，我们引入NT-ASGD，平均随机梯度方法的变体，其中平均触发是使用非单调条件确定的，而不是由用户调整。使用这些和其他正则化策略，我们在两个数据集上实现了最先进的字级困惑：Penn Treebank上的57.3和WikiText-2上的65.8。在结合我们提出的模型探索神经缓存的有效性时，我们在Penn Treebank上实现了更低的52.8的最新困惑性，而在WikiText-2上达到了52.0。

##### URL
[https://arxiv.org/abs/1708.02182](https://arxiv.org/abs/1708.02182)

##### PDF
[https://arxiv.org/pdf/1708.02182](https://arxiv.org/pdf/1708.02182)

