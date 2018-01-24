---
layout: post
title: "Query Focused Abstractive Summarization: Incorporating Query Relevance, Multi-Document Coverage, and Summary Length Constraints into seq2seq Models"
date: 2018-01-23 18:47:03
categories: arXiv_CL
tags: arXiv_CL Attention Summarization
author: Tal Baumel, Matan Eyal, Michael Elhadad
mathjax: true
---

* content
{:toc}

##### Abstract
Query Focused Summarization (QFS) has been addressed mostly using extractive methods. Such methods, however, produce text which suffers from low coherence. We investigate how abstractive methods can be applied to QFS, to overcome such limitations. Recent developments in neural-attention based sequence-to-sequence models have led to state-of-the-art results on the task of abstractive generic single document summarization. Such models are trained in an end to end method on large amounts of training data. We address three aspects to make abstractive summarization applicable to QFS: (a)since there is no training data, we incorporate query relevance into a pre-trained abstractive model; (b) since existing abstractive models are trained in a single-document setting, we design an iterated method to embed abstractive models within the multi-document requirement of QFS; (c) the abstractive models we adapt are trained to generate text of specific length (about 100 words), while we aim at generating output of a different size (about 250 words); we design a way to adapt the target size of the generated summaries to a given size ratio. We compare our method (Relevance Sensitive Attention for QFS) to extractive baselines and with various ways to combine abstractive models on the DUC QFS datasets and demonstrate solid improvements on ROUGE performance.

##### Abstract (translated by Google)
查询聚焦总结（QFS）已经被大多数使用提取方法解决。然而，这样的方法产生了低连贯性的文本。我们调查抽象方法如何应用于QFS，克服这些限制。最近在基于神经注意的序列到序列模型中的发展导致了对抽象通用单一文档摘要任务的最新结果。这种模型在大量训练数据的端到端方法训练。 （a）由于没有训练数据，我们将查询相关性纳入预训练的抽象模型中; （b）由于现有的抽象模型是在单一文档环境下进行训练的，我们设计了一个迭代方法来将抽象模型嵌入到QFS的多文档需求中; （c）我们适应的抽象模型被训练成产生特定长度的文本（大约100个字），而我们的目标是产生不同大小的输出（大约250个字）。我们设计一种方法来将生成的摘要的目标大小调整为给定的大小比例。我们将我们的方法（针对QFS的相关性敏感注意）与抽取基线进行比较，并以各种方式将DUC QFS数据集上的抽象模型相结合，并对ROUGE性能进行了可靠的改进。

##### URL
[http://arxiv.org/abs/1801.07704](http://arxiv.org/abs/1801.07704)

##### PDF
[http://arxiv.org/pdf/1801.07704](http://arxiv.org/pdf/1801.07704)

