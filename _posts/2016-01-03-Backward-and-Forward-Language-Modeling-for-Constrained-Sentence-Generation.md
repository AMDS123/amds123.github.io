---
layout: post
title: "Backward and Forward Language Modeling for Constrained Sentence Generation"
date: 2016-01-03 20:15:44
categories: arXiv_CL
tags: arXiv_CL Summarization RNN Language_Model
author: Lili Mou, Rui Yan, Ge Li, Lu Zhang, Zhi Jin
mathjax: true
---

* content
{:toc}

##### Abstract
Recent language models, especially those based on recurrent neural networks (RNNs), make it possible to generate natural language from a learned probability. Language generation has wide applications including machine translation, summarization, question answering, conversation systems, etc. Existing methods typically learn a joint probability of words conditioned on additional information, which is (either statically or dynamically) fed to RNN's hidden layer. In many applications, we are likely to impose hard constraints on the generated texts, i.e., a particular word must appear in the sentence. Unfortunately, existing approaches could not solve this problem. In this paper, we propose a novel backward and forward language model. Provided a specific word, we use RNNs to generate previous words and future words, either simultaneously or asynchronously, resulting in two model variants. In this way, the given word could appear at any position in the sentence. Experimental results show that the generated texts are comparable to sequential LMs in quality.

##### Abstract (translated by Google)
最近的语言模型，特别是基于递归神经网络（RNN）的语言模型，使得从学习概率生成自然语言成为可能。语言生成具有广泛的应用，包括机器翻译，摘要，问答，会话系统等。现有方法通常学习以附加信息为条件的联合概率，该信息是（静态地或动态地）馈送到RNN的隐藏层。在许多应用中，我们可能会对生成的文本施加严格的约束，即一个特定的单词必须出现在句子中。不幸的是，现有的方法无法解决这个问题。在本文中，我们提出了一种新颖的前向和后向语言模型。提供了一个特定的词，我们使用RNN生成以前的单词和未来的单词，同时或异步，导致两个模型变种。这样，给定的单词就可以出现在句子的任何位置。实验结果表明，生成的文本在质量上与连续的LM相当。

##### URL
[https://arxiv.org/abs/1512.06612](https://arxiv.org/abs/1512.06612)

##### PDF
[https://arxiv.org/pdf/1512.06612](https://arxiv.org/pdf/1512.06612)

