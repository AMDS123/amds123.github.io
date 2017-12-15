---
layout: post
title: "Mimicking Word Embeddings using Subword RNNs"
date: 2017-07-21 16:18:10
categories: arXiv_CL
tags: arXiv_CL Embedding RNN
author: Yuval Pinter, Robert Guthrie, Jacob Eisenstein
mathjax: true
---

* content
{:toc}

##### Abstract
Word embeddings improve generalization over lexical features by placing each word in a lower-dimensional space, using distributional information obtained from unlabeled data. However, the effectiveness of word embeddings for downstream NLP tasks is limited by out-of-vocabulary (OOV) words, for which embeddings do not exist. In this paper, we present MIMICK, an approach to generating OOV word embeddings compositionally, by learning a function from spellings to distributional embeddings. Unlike prior work, MIMICK does not require re-training on the original word embedding corpus; instead, learning is performed at the type level. Intrinsic and extrinsic evaluations demonstrate the power of this simple approach. On 23 languages, MIMICK improves performance over a word-based baseline for tagging part-of-speech and morphosyntactic attributes. It is competitive with (and complementary to) a supervised character-based model in low-resource settings.

##### Abstract (translated by Google)
词嵌入通过使用从未标记的数据获得的分布信息将每个词放置在较低维度的空间中而改进对词汇特征的泛化。然而，词嵌入对于下游NLP任务的有效性受到词汇外（OOV）词的限制，词不存在嵌入。在本文中，我们介绍MIMICK，一种通过学习从拼写到分布式嵌入的函数在组合上产生OOV字嵌入的方法。与之前的工作不同，MIMICK不需要对原始单词嵌入语料库进行重新训练;相反，学习是在类型级别上进行的。内在和外在的评估证明了这种简单方法的力量。在23种语言中，MIMICK提高了基于单词的基线的性能，用于标记词性和形态句法属性。它在低资源环境中与基于角色的监督模型相比具有竞争性（并且是相辅相成的）。

##### URL
[https://arxiv.org/abs/1707.06961](https://arxiv.org/abs/1707.06961)

##### PDF
[https://arxiv.org/pdf/1707.06961](https://arxiv.org/pdf/1707.06961)

