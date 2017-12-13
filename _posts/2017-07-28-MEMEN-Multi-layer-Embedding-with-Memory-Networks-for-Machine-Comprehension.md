---
layout: post
title: "MEMEN: Multi-layer Embedding with Memory Networks for Machine Comprehension"
date: 2017-07-28 03:41:18
categories: arXiv_CV
tags: arXiv_CV QA Attention Embedding Memory_Networks
author: Boyuan Pan, Hao Li, Zhou Zhao, Bin Cao, Deng Cai, Xiaofei He
mathjax: true
---

* content
{:toc}

##### Abstract
Machine comprehension(MC) style question answering is a representative problem in natural language processing. Previous methods rarely spend time on the improvement of encoding layer, especially the embedding of syntactic information and name entity of the words, which are very crucial to the quality of encoding. Moreover, existing attention methods represent each query word as a vector or use a single vector to represent the whole query sentence, neither of them can handle the proper weight of the key words in query sentence. In this paper, we introduce a novel neural network architecture called Multi-layer Embedding with Memory Network(MEMEN) for machine reading task. In the encoding layer, we employ classic skip-gram model to the syntactic and semantic information of the words to train a new kind of embedding layer. We also propose a memory network of full-orientation matching of the query and passage to catch more pivotal information. Experiments show that our model has competitive results both from the perspectives of precision and efficiency in Stanford Question Answering Dataset(SQuAD) among all published results and achieves the state-of-the-art results on TriviaQA dataset.

##### Abstract (translated by Google)
机器理解（MC）式问题回答是自然语言处理中的代表性问题。以前的方法很少花费时间在编码层的改进上，特别是句子信息和单词名称实体的嵌入，这对于编码质量是非常关键的。另外，现有的关注方法是将每个查询词表示为一个向量，或者用单个向量来表示整个查询语句，他们都不能处理查询语句中关键词的权重。在本文中，我们介绍了一种新的神经网络架构称为多层嵌入式存储器网络（MEMEN）的机器阅读任务。在编码层中，我们采用经典的skip-gram模型对单词的句法和语义信息进行训练，以训练一种新的嵌入层。我们还提出了一个全方位的查询和段落匹配的记忆网络，以获取更多的关键信息。实验表明，我们的模型在斯坦福问答数据集（SQUAD）的精度和效率方面都具有相当的竞争力，并在TriviaQA数据集上取得了最新的成果。

##### URL
[https://arxiv.org/abs/1707.09098](https://arxiv.org/abs/1707.09098)

##### PDF
[https://arxiv.org/pdf/1707.09098](https://arxiv.org/pdf/1707.09098)

