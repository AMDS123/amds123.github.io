---
layout: post
title: "Neural Language Modeling by Jointly Learning Syntax and Lexicon"
date: 2018-02-19 04:48:35
categories: arXiv_AI
tags: arXiv_AI RNN Language_Model
author: Yikang Shen, Zhouhan Lin, Chin-Wei Huang, Aaron Courville
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a neural language model capable of unsupervised syntactic structure induction. The model leverages the structure information to form better semantic representations and better language modeling. Standard recurrent neural networks are limited by their structure and fail to efficiently use syntactic information. On the other hand, tree-structured recursive networks usually require additional structural supervision at the cost of human expert annotation. In this paper, We propose a novel neural language model, called the Parsing-Reading-Predict Networks (PRPN), that can simultaneously induce the syntactic structure from unannotated sentences and leverage the inferred structure to learn a better language model. In our model, the gradient can be directly back-propagated from the language model loss into the neural parsing network. Experiments show that the proposed model can discover the underlying syntactic structure and achieve state-of-the-art performance on word/character-level language model tasks.

##### Abstract (translated by Google)
我们提出了一种能够无监督句法结构归纳的神经语言模型。该模型利用结构信息来形成更好的语义表示和更好的语言建模。标准递归神经网络受其结构限制，无法有效地使用句法信息。另一方面，树形结构的递归网络通常需要额外的结构监督，但要以人工专家注释为代价。在本文中，我们提出了一种新的神经语言模型，称为分析 - 阅读 - 预测网络（PRPN），它可以同时从未注释的句子引发句法结构，并利用推断的结构学习更好的语言模型。在我们的模型中，梯度可以从语言模型损失直接反向传播到神经解析网络。实验表明，所提出的模型可以发现潜在的句法结构，并在单词/字符级语言模型任务上实现最先进的性能。

##### URL
[http://arxiv.org/abs/1711.02013](http://arxiv.org/abs/1711.02013)

##### PDF
[http://arxiv.org/pdf/1711.02013](http://arxiv.org/pdf/1711.02013)

