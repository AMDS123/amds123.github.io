---
layout: post
title: "Recurrent Neural Network Language Model Adaptation Derived Document Vector"
date: 2016-11-01 12:14:02
categories: arXiv_CL
tags: arXiv_CL RNN Classification Language_Model Relation
author: Wei Li, Brian Kan Wing Mak
mathjax: true
---

* content
{:toc}

##### Abstract
In many natural language processing (NLP) tasks, a document is commonly modeled as a bag of words using the term frequency-inverse document frequency (TF-IDF) vector. One major shortcoming of the frequency-based TF-IDF feature vector is that it ignores word orders that carry syntactic and semantic relationships among the words in a document, and they can be important in some NLP tasks such as genre classification. This paper proposes a novel distributed vector representation of a document: a simple recurrent-neural-network language model (RNN-LM) or a long short-term memory RNN language model (LSTM-LM) is first created from all documents in a task; some of the LM parameters are then adapted by each document, and the adapted parameters are vectorized to represent the document. The new document vectors are labeled as DV-RNN and DV-LSTM respectively. We believe that our new document vectors can capture some high-level sequential information in the documents, which other current document representations fail to capture. The new document vectors were evaluated in the genre classification of documents in three corpora: the Brown Corpus, the BNC Baby Corpus and an artificially created Penn Treebank dataset. Their classification performances are compared with the performance of TF-IDF vector and the state-of-the-art distributed memory model of paragraph vector (PV-DM). The results show that DV-LSTM significantly outperforms TF-IDF and PV-DM in most cases, and combinations of the proposed document vectors with TF-IDF or PV-DM may further improve performance.

##### Abstract (translated by Google)
在许多自然语言处理（NLP）任务中，通常使用术语频率逆文档频率（TF-IDF）向量来将文档建模为一包字。基于频率的TF-IDF特征向量的一个主要缺点是它忽略了在文档中的词语之间存在句法和语义关系的词序，并且它们对于一些NLP任务（诸如体裁分类）可能是重要的。本文提出了一种新的分布式文档向量表示方法：首先从一个任务的所有文档中创建一个简单的递归神经网络语言模型（RNN-LM）或一个长期的短期记忆RNN语言模型（LSTM-LM） ;一些LM参数随后由每个文档调整，并且适配的参数被矢量化以表示文档。新的文档向量分别标记为DV-RNN和DV-LSTM。我们相信，我们的新的文档向量可以捕获文档中的一些高层次的顺序信息，其他当前文档表示无法捕获。新的文档向量在三个语料库中的文档的流派分类中进行评估：布朗语料库，BNC婴儿语料库和人为创建的宾州树库数据集。将它们的分类性能与TF-IDF矢量的性能和现有技术中的段矢量分布式存储器模型（PV-DM）进行比较。结果表明，DV-LSTM在大多数情况下明显优于TF-IDF和PV-DM，并且所提出的文档向量与TF-IDF或PV-DM的组合可以进一步提高性能。

##### URL
[https://arxiv.org/abs/1611.00196](https://arxiv.org/abs/1611.00196)

##### PDF
[https://arxiv.org/pdf/1611.00196](https://arxiv.org/pdf/1611.00196)

