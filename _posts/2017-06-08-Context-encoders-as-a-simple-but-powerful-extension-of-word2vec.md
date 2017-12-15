---
layout: post
title: "Context encoders as a simple but powerful extension of word2vec"
date: 2017-06-08 09:56:11
categories: arXiv_CL
tags: arXiv_CL Embedding Language_Model Recognition
author: Franziska Horn
mathjax: true
---

* content
{:toc}

##### Abstract
With a simple architecture and the ability to learn meaningful word embeddings efficiently from texts containing billions of words, word2vec remains one of the most popular neural language models used today. However, as only a single embedding is learned for every word in the vocabulary, the model fails to optimally represent words with multiple meanings. Additionally, it is not possible to create embeddings for new (out-of-vocabulary) words on the spot. Based on an intuitive interpretation of the continuous bag-of-words (CBOW) word2vec model's negative sampling training objective in terms of predicting context based similarities, we motivate an extension of the model we call context encoders (ConEc). By multiplying the matrix of trained word2vec embeddings with a word's average context vector, out-of-vocabulary (OOV) embeddings and representations for a word with multiple meanings can be created based on the word's local contexts. The benefits of this approach are illustrated by using these word embeddings as features in the CoNLL 2003 named entity recognition (NER) task.

##### Abstract (translated by Google)
word2vec具有简单的架构，能够从包含数十亿字的文本中有效地学习有意义的词嵌入，而且仍然是当今最流行的神经语言模型之一。然而，由于词汇表中的每个单词只有一个嵌入，所以该模型不能最佳地表示具有多重含义的单词。另外，不可能在现场为新的（词汇外）单词创建嵌入。基于连续词袋（CBOW）word2vec模型的负面抽样训练目标（就预测基于上下文的相似性而言）的直观解释，我们激发对我们称为上下文编码器（ConEc）的模型的扩展。通过将训练过的word2vec嵌入的矩阵与单词的平均上下文向量相乘，可以基于单词的本地上下文创建词汇表（OOV）嵌入和表示具有多种含义的单词。这种方法的好处通过在CoNLL 2003命名实体识别（NER）任务中使用这些词嵌入作为特征来说明。

##### URL
[https://arxiv.org/abs/1706.02496](https://arxiv.org/abs/1706.02496)

##### PDF
[https://arxiv.org/pdf/1706.02496](https://arxiv.org/pdf/1706.02496)

