---
layout: post
title: "Fine-grained Analysis of Sentence Embeddings Using Auxiliary Prediction Tasks"
date: 2017-02-09 06:58:50
categories: arXiv_CL
tags: arXiv_CL Embedding RNN Deep_Learning Prediction
author: Yossi Adi, Einat Kermany, Yonatan Belinkov, Ofer Lavi, Yoav Goldberg
mathjax: true
---

* content
{:toc}

##### Abstract
There is a lot of research interest in encoding variable length sentences into fixed length vectors, in a way that preserves the sentence meanings. Two common methods include representations based on averaging word vectors, and representations based on the hidden states of recurrent neural networks such as LSTMs. The sentence vectors are used as features for subsequent machine learning tasks or for pre-training in the context of deep learning. However, not much is known about the properties that are encoded in these sentence representations and about the language information they capture. We propose a framework that facilitates better understanding of the encoded representations. We define prediction tasks around isolated aspects of sentence structure (namely sentence length, word content, and word order), and score representations by the ability to train a classifier to solve each prediction task when using the representation as input. We demonstrate the potential contribution of the approach by analyzing different sentence representation mechanisms. The analysis sheds light on the relative strengths of different sentence embedding methods with respect to these low level prediction tasks, and on the effect of the encoded vector's dimensionality on the resulting representations.

##### Abstract (translated by Google)
将可变长度的句子编码成固定长度的矢量有很多研究兴趣，这样可以保留句子的含义。两种常见的方法包括基于平均单词向量的表示，以及基于隐式状态的递归神经网络如LSTM的表示。句子向量被用作后续机器学习任务的特征或用于深度学习的预训练。然而，关于在这些句子表示中编码的属性以及它们所捕获的语言信息知之甚少。我们提出了一个框架，有助于更好地理解编码表示。我们定义了句子结构（即句子长度，单词内容和单词顺序）的孤立方面的预测任务，并通过训练一个分类器来解决每个预测任务的能力来评分表示。我们通过分析不同的句子表示机制来证明该方法的潜在贡献。分析揭示了不同的句子嵌入方法相对于这些低级预测任务的相对强度，以及编码矢量的维度对所得表示的影响。

##### URL
[https://arxiv.org/abs/1608.04207](https://arxiv.org/abs/1608.04207)

##### PDF
[https://arxiv.org/pdf/1608.04207](https://arxiv.org/pdf/1608.04207)

