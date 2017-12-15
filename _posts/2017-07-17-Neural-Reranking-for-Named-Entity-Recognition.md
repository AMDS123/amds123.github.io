---
layout: post
title: "Neural Reranking for Named Entity Recognition"
date: 2017-07-17 12:57:53
categories: arXiv_CL
tags: arXiv_CL Sparse RNN Recognition
author: Jie Yang, Yue Zhang, Fei Dong
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a neural reranking system for named entity recognition (NER). The basic idea is to leverage recurrent neural network models to learn sentence-level patterns that involve named entity mentions. In particular, given an output sentence produced by a baseline NER model, we replace all entity mentions, such as \textit{Barack Obama}, into their entity types, such as \textit{PER}. The resulting sentence patterns contain direct output information, yet is less sparse without specific named entities. For example, "PER was born in LOC" can be such a pattern. LSTM and CNN structures are utilised for learning deep representations of such sentences for reranking. Results show that our system can significantly improve the NER accuracies over two different baselines, giving the best reported results on a standard benchmark.

##### Abstract (translated by Google)
我们提出了一个名为实体识别（NER）的神经网络排序系统。基本思想是利用递归神经网络模型来学习涉及命名实体提及的句子级模式。具体来说，给定一个由基线NER模型产生的输出句子，我们将所有实体提及，例如\ textit {Barack Obama}，替换为它们的实体类型，例如\ textit {PER}。得到的句子模式包含直接的输出信息，但没有特定的命名实体就不那么稀疏了。例如，“PER出生在LOC”就可以是这样一种模式。利用LSTM和CNN结构来学习这些句子的深度表示来进行排序。结果表明，我们的系统能够显着提高两个不同基线的NER精度，在标准基准上得到最好的报告结果。

##### URL
[https://arxiv.org/abs/1707.05127](https://arxiv.org/abs/1707.05127)

##### PDF
[https://arxiv.org/pdf/1707.05127](https://arxiv.org/pdf/1707.05127)

