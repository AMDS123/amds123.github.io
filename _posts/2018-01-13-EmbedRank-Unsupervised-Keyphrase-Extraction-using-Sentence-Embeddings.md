---
layout: post
title: "EmbedRank: Unsupervised Keyphrase Extraction using Sentence Embeddings"
date: 2018-01-13 17:57:33
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Kamil Bennani-Smires, Claudiu Musat, Martin Jaggi, Andreea Hossmann, Michael Baeriswyl
mathjax: true
---

* content
{:toc}

##### Abstract
Keyphrase extraction is the task of automatically selecting a small set of phrases that best describe a given free text document. Keyphrases can be used for indexing, searching, aggregating and summarizing text documents, serving many automatic as well as human-facing use cases. Existing supervised systems for keyphrase extraction require large amounts of labeled training data and generalize very poorly outside the domain of the training data. At the same time, unsupervised systems found in the literature have poor accuracy, and often do not generalize well, as they require the input document to belong to a larger corpus also given as input. Furthermore, both supervised and unsupervised methods are often too slow for real-time scenarios and suffer from over-generation. Addressing these drawbacks, in this paper, we introduce an unsupervised method for keyphrase extraction from single documents that leverages sentence embeddings. By selecting phrases whose semantic embeddings are close to the embeddings of the whole document, we are able to separate the best candidate phrases from the rest. We show that our embedding-based method is not only simpler, but also more effective than graph-based state of the art systems, achieving higher F-scores on standard datasets. Simplicity is a significant advantage, especially when processing large amounts of documents from the Web, resulting in considerable speed gains. Moreover, we describe how to increase coverage and diversity among the selected keyphrases by introducing an embedding-based maximal marginal relevance (MMR) for new phrases. A user study including over 200 votes showed that, although reducing the phrase semantic overlap leads to no gains in terms of F-score, our diversity enriched selection is preferred by humans.

##### Abstract (translated by Google)
关键词提取是自动选择最能描述给定自由文本文档的一组短语的任务。关键字可用于索引，搜索，汇总和汇总文本文档，为许多自动以及面向人的用例提供服务。用于关键词提取的现有监督系统需要大量标记的训练数据，并且在训练数据的领域之外将其概括得很差。同时，在文献中发现的无监督系统的准确性较差，而且往往不能很好地概括，因为它们要求输入文档属于也作为输入的较大的语料库。而且，有监督和无监督的方法对于实时情况来说通常太慢，并且会受到过度的影响。为了解决这些缺点，在本文中，我们介绍了一个无监督的方法，用于从单个文档中提取关键词的句法嵌入。通过选择其语义嵌入接近整个文档的嵌入的短语，我们能够将最好的候选短语与其余的分开。我们表明，基于嵌入的方法不仅简单，而且比基于图形的现有系统更有效，在标准数据集上获得更高的F分数。简单性是一个显着的优势，特别是在处理来自Web的大量文档时，会带来相当大的速度提升。此外，我们描述了如何通过引入基于嵌入的新词组的最大边际相关性（MMR）来增加所选关键词的覆盖范围和多样性。包括超过200张选票的用户研究表明，虽然减少短语语义重叠导致在F评分方面没有收益，但我们的多样性丰富的选择是人类首选的。

##### URL
[http://arxiv.org/abs/1801.04470](http://arxiv.org/abs/1801.04470)

##### PDF
[http://arxiv.org/pdf/1801.04470](http://arxiv.org/pdf/1801.04470)

