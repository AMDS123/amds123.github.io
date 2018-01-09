---
layout: post
title: "Unsupervised Low-Dimensional Vector Representations for Words, Phrases and Text that are Transparent, Scalable, and produce Similarity Metrics that are Complementary to Neural Embeddings"
date: 2018-01-05 19:00:04
categories: arXiv_CL
tags: arXiv_CL Face Embedding Language_Model
author: Neil R. Smalheiser, Gary Bonifield
mathjax: true
---

* content
{:toc}

##### Abstract
Neural embeddings are a popular set of methods for representing words, phrases or text as a low dimensional vector (typically 50-500 dimensions). However, it is difficult to interpret these dimensions in a meaningful manner, and creating neural embeddings requires extensive training and tuning of multiple parameters and hyperparameters. We present here a simple unsupervised method for representing words, phrases or text as a low dimensional vector, in which the meaning and relative importance of dimensions is transparent to inspection. We have created a near-comprehensive vector representation of words, and selected bigrams, trigrams and abbreviations, using the set of titles and abstracts in PubMed as a corpus. This vector is used to create several novel implicit word-word and text-text similarity metrics. The implicit word-word similarity metrics correlate well with human judgement of word pair similarity and relatedness, and outperform or equal all other reported methods on a variety of biomedical benchmarks, including several implementations of neural embeddings trained on PubMed corpora. Our implicit word-word metrics capture different aspects of word-word relatedness than word2vec-based metrics and are only partially correlated (rho = ~0.5-0.8 depending on task and corpus). The vector representations of words, bigrams, trigrams, abbreviations, and PubMed title+abstracts are all publicly available from <a href="http://arrowsmith.psych.uic.edu">this http URL</a> for release under CC-BY-NC license. Several public web query interfaces are also available at the same site, including one which allows the user to specify a given word and view its most closely related terms according to direct co-occurrence as well as different implicit similarity metrics.

##### Abstract (translated by Google)
神经嵌入是用于将单词，短语或文本表示为低维向量（通常为50-500维度）的流行的一组方法。然而，以有意义的方式来解释这些维度是困难的，并且创建神经嵌入需要对多个参数和超参数进行大量的训练和调整。我们在这里提出一个简单的无监督的方法来表示单词，短语或文本作为一个低维矢量，其中维的意义和相对重要性是透明的检查。我们创建了一个近乎全面的单词向量表示形式，并将PubMed中的标题和摘要作为一个语料库，选择了两个词，三元组和缩略词。这个向量用来创建几个新颖的隐含的单词和文本文本相似性度量。隐含词 - 词相似性度量与人类对词对相似度和相关度的判断相关性良好，在各种生物医学基准测试中均优于或等于所有其他报道的方法，包括在PubMed语料库上训练的神经嵌入的几个实现。我们的隐含单词指标捕捉单词相关性的不同方面比基于word2vec的指标，并且只是部分相关（rho =〜0.5-0.8取决于任务和语料库）。词，bigrams，trigrams，缩写和PubMed标题+摘要的向量表示都可以从<a href="http://arrowsmith.psych.uic.edu">这个http URL </a>公开发布CC-BY-NC许可证。在同一个站点上还有几个公共网页查询接口，包括允许用户指定一个给定的单词，并根据直接共现以及不同的隐式相似性度量来查看其最紧密相关的术语。

##### URL
[http://arxiv.org/abs/1801.01884](http://arxiv.org/abs/1801.01884)

##### PDF
[http://arxiv.org/pdf/1801.01884](http://arxiv.org/pdf/1801.01884)

