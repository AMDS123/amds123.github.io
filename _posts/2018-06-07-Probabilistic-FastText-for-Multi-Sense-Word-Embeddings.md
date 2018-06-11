---
layout: post
title: "Probabilistic FastText for Multi-Sense Word Embeddings"
date: 2018-06-07 20:57:22
categories: arXiv_AI
tags: arXiv_AI Embedding
author: Ben Athiwaratkun, Andrew Gordon Wilson, Anima Anandkumar
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce Probabilistic FastText, a new model for word embeddings that can capture multiple word senses, sub-word structure, and uncertainty information. In particular, we represent each word with a Gaussian mixture density, where the mean of a mixture component is given by the sum of n-grams. This representation allows the model to share statistical strength across sub-word structures (e.g. Latin roots), producing accurate representations of rare, misspelt, or even unseen words. Moreover, each component of the mixture can capture a different word sense. Probabilistic FastText outperforms both FastText, which has no probabilistic model, and dictionary-level probabilistic embeddings, which do not incorporate subword structures, on several word-similarity benchmarks, including English RareWord and foreign language datasets. We also achieve state-of-art performance on benchmarks that measure ability to discern different meanings. Thus, the proposed model is the first to achieve multi-sense representations while having enriched semantics on rare words.

##### Abstract (translated by Google)
我们引入了Probabilistic FastText，这是一种新的词嵌入模型，可以捕获多个词义，子词结构和不确定性信息。特别是，我们用高斯混合密度来表示每个单词，其中混合分量的平均值由n-gram的总和给出。这种表示形式允许模型跨越子词结构（例如拉丁语根）共享统计强度，从而生成罕见，拼写错误或甚至看不见的单词的准确表示。而且，混合物的每个组分都可以捕获不同的词义。概率FastText优于没有概率模型的FastText和不包含子字词结构的字典级概率嵌入在几个包括英文RareWord和外语数据集的词相似性基准测试中。我们还在衡量识别不同含义的能力基准测试中取得了最先进的表现。因此，所提出的模型是第一个实现多义表示，同时丰富了稀有词语的语义。

##### URL
[http://arxiv.org/abs/1806.02901](http://arxiv.org/abs/1806.02901)

##### PDF
[http://arxiv.org/pdf/1806.02901](http://arxiv.org/pdf/1806.02901)

