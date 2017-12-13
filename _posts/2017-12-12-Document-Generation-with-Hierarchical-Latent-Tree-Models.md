---
layout: post
title: "Document Generation with Hierarchical Latent Tree Models"
date: 2017-12-12 04:07:10
categories: arXiv_CL
tags: arXiv_CL Detection
author: Peixian Chen, Zhourong Chen, Nevin L. Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
In most probabilistic topic models, a document is viewed as a collection of tokens and each token is a variable whose values are all the words in a vocabulary. One exception is hierarchical latent tree models (HLTMs), where a document is viewed as a binary vector over the vocabulary and each word is regarded as a binary variable. The use of word variables allows the detection and representation of patterns of word co-occurrences and co-occurrences of those patterns qualitatively using multiple levels of latent variables, and naturally leads to a method for hierarchical topic detection. In this paper, we assume that an HLTM has been learned from binary data and we extend it to take word frequencies into consideration. The idea is to replace each binary word variable with a real-valued variable that represents the relative frequency of the word in a document. A document generation process is proposed and an algorithm is given for estimating the model parameters by inverting the generation process. Empirical results show that our method significantly outperforms the commonly-used LDA-based methods for hierarchical topic detection, in terms of model quality and meaningfulness of topics and topic hierarchies.

##### Abstract (translated by Google)
在大多数概率主题模型中，文档被看作是一个记号的集合，而每个记号是一个变量，其值是词汇表中的所有单词。一个例外是分层潜在树模型（HLTM），其中文档在词汇表中被视为二进制向量，每个词被视为二进制变量。词变量的使用使得能够定性地使用多个潜在变量级来检测和表示词共现模式和这些模式的共现，并且自然地导致用于分层主题检测的方法。在本文中，我们假设一个HLTM已经从二进制数据中学习，我们扩展它来考虑词频。这个想法是用一个代表文档中单词相对频率的实值变量代替每个二进制字变量。提出了一个文档生成过程，并给出了一个算法，通过反演生成过程来估计模型参数。实证结果表明，我们的方法在模型质量和主题和主题层次的意义方面明显优于常用的基于LDA的分层主题检测方法。

##### URL
[http://arxiv.org/abs/1712.04116](http://arxiv.org/abs/1712.04116)

##### PDF
[http://arxiv.org/pdf/1712.04116](http://arxiv.org/pdf/1712.04116)

