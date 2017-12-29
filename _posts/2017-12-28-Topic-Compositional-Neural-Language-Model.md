---
layout: post
title: "Topic Compositional Neural Language Model"
date: 2017-12-28 08:05:48
categories: arXiv_CL
tags: arXiv_CL RNN Language_Model
author: Wenlin Wang, Zhe Gan, Wenqi Wang, Dinghan Shen, Jiaji Huang, Wei Ping, Sanjeev Satheesh, Lawrence Carin
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a Topic Compositional Neural Language Model (TCNLM), a novel method designed to simultaneously capture both the global semantic meaning and the local word ordering structure in a document. The TCNLM learns the global semantic coherence of a document via a neural topic model, and the probability of each learned latent topic is further used to build a Mixture-of-Experts (MoE) language model, where each expert (corresponding to one topic) is a recurrent neural network (RNN) that accounts for learning the local structure of a word sequence. In order to train the MoE model efficiently, a matrix factorization method is applied, by extending each weight matrix of the RNN to be an ensemble of topic-dependent weight matrices. The degree to which each member of the ensemble is used is tied to the document-dependent probability of the corresponding topics. Experimental results on several corpora show that the proposed approach outperforms both a pure RNN-based model and other topic-guided language models. Further, our model yields sensible topics, and also has the capacity to generate meaningful sentences conditioned on given topics.

##### Abstract (translated by Google)
我们提出了一个主题组合神经语言模型（TCNLM），一种新颖的方法，旨在同时捕捉文档中的全局语义和本地词语排序结构。 TCNLM通过神经主题模型学习文档的全局语义连贯性，并且将每个学习到的潜在主题的概率进一步用于构建专家混合（MoE）语言模型，其中每个专家（对应于一个主题）是一个循环神经网络（RNN），它解释了学习单词序列的局部结构。为了有效地训练MoE模型，应用矩阵分解方法，将RNN的每个权重矩阵扩展为与主题相关的权重矩阵的集合。使用集合的每个成员的程度与相应主题的依赖于文档的概率相关联。在几个语料上的实验结果表明，所提出的方法优于纯粹的基于RNN的模型和其他主题引导的语言模型。此外，我们的模型产生明智的话题，也有能力产生有条件的话题的有意义的句子。

##### URL
[http://arxiv.org/abs/1712.09783](http://arxiv.org/abs/1712.09783)

##### PDF
[http://arxiv.org/pdf/1712.09783](http://arxiv.org/pdf/1712.09783)

