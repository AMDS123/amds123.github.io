---
layout: post
title: "Semi-Supervised Multi-Task Word Embeddings"
date: 2018-09-16 14:36:54
categories: arXiv_CL
tags: arXiv_CL Embedding Relation
author: James O&#x27; Neill, Danushka Bollegala
mathjax: true
---

* content
{:toc}

##### Abstract
Word embeddings have been shown to benefit from ensembling several word embedding sources, often carried out using straightforward mathematical operations over the set of vectors to produce a meta-embedding representation. More recently, unsupervised learning has been used to find a lower-dimensional representation, similar in size to that of the word embeddings within the ensemble. However, these methods do not use the available manual labeled datasets that are often used solely for the purpose of evaluation. 
 We propose to improve word embeddings by simultaneously learning to reconstruct an ensemble of pretrained word embeddings with supervision from various labeled word similarity datasets. This involves reconstructing word meta-embeddings while simultaneously using a Siamese Network to also learn word similarity where both processes share a hidden layer. Experiments are carried out on 6 word similarity datasets and 3 analogy datasets. We find that performance is improved for all word similarity datasets when compared to unsupervised learning methods with a mean increase of 11.33 in the Spearman Correlation coefficient. Moreover, 4 of 6 of word similarity datasets from our approach show best performance when using of a cosine loss for reconstruction and Brier's loss for word similarity.

##### Abstract (translated by Google)
已经证明，字嵌入受益于集合几个字嵌入源，通常使用对该组矢量的直接数学运算来执行以产生元嵌入表示。最近，已经使用无监督学习来找到低维表示，其尺寸类似于整体内的单词嵌入的大小。但是，这些方法不使用通常仅用于评估目的的可用手动标记数据集。
 我们建议通过同时学习在各种标记的单词相似性数据集的监督下重建预训练单词嵌入的集合来改进单词嵌入。这涉及重建单词元嵌入，同时使用连体网络来学习单词相似性，其中两个进程共享隐藏层。对6个字相似性数据集和3个类比数据集进行实验。我们发现，与无监督学习方法相比，所有单词相似性数据集的性能都得到了提高，Spearman相关系数平均增加了11.33。此外，当使用余弦损失进行重建和Brier的单词相似性损失时，来自我们方法的6个单词相似性数据集中的4个表现出最佳性能。

##### URL
[http://arxiv.org/abs/1809.05886](http://arxiv.org/abs/1809.05886)

##### PDF
[http://arxiv.org/pdf/1809.05886](http://arxiv.org/pdf/1809.05886)

