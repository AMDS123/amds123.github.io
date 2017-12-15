---
layout: post
title: "Improve Lexicon-based Word Embeddings By Word Sense Disambiguation"
date: 2017-07-24 16:07:01
categories: arXiv_CL
tags: arXiv_CL Text_Classification Embedding Classification
author: Yuanzhi Ke, Masafumi Hagiwara
mathjax: true
---

* content
{:toc}

##### Abstract
There have been some works that learn a lexicon together with the corpus to improve the word embeddings. However, they either model the lexicon separately but update the neural networks for both the corpus and the lexicon by the same likelihood, or minimize the distance between all of the synonym pairs in the lexicon. Such methods do not consider the relatedness and difference of the corpus and the lexicon, and may not be the best optimized. In this paper, we propose a novel method that considers the relatedness and difference of the corpus and the lexicon. It trains word embeddings by learning the corpus to predicate a word and its corresponding synonym under the context at the same time. For polysemous words, we use a word sense disambiguation filter to eliminate the synonyms that have different meanings for the context. To evaluate the proposed method, we compare the performance of the word embeddings trained by our proposed model, the control groups without the filter or the lexicon, and the prior works in the word similarity tasks and text classification task. The experimental results show that the proposed model provides better embeddings for polysemous words and improves the performance for text classification.

##### Abstract (translated by Google)
已经有一些作品与语料库一起学习一个词库来改进词嵌入。然而，他们要么单独建立词典的模型，要么以相同的可能性更新语料库和词典的神经网络，要么最小化词典中所有同义词对之间的距离。这样的方法不考虑语料库和词典的关联性和差异性，不一定是最优化的。在本文中，我们提出了一种新的方法，考虑到语料库和词汇的相关性和差异性。它通过学习语料来训练单词嵌入，同时在上下文中预测单词及其相应的同义词。对于多义词，我们使用词义消歧过滤器来消除对于上下文具有不同含义的同义词。为了评估所提出的方法，我们比较了由我们提出的模型训练的单词嵌入，没有过滤器或词典的控制组，以及先前在单词相似性任务和文本分类任务中的性能。实验结果表明，该模型为多义词提供了更好的嵌入，提高了文本分类的性能。

##### URL
[https://arxiv.org/abs/1707.07628](https://arxiv.org/abs/1707.07628)

##### PDF
[https://arxiv.org/pdf/1707.07628](https://arxiv.org/pdf/1707.07628)

