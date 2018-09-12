---
layout: post
title: "Improved Sentence Modeling using Suffix Bidirectional LSTM"
date: 2018-09-10 22:16:36
categories: arXiv_AI
tags: arXiv_AI Sentiment Sentiment_Classification Text_Classification RNN Classification Detection
author: Siddhartha Brahma
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks have become ubiquitous in computing representations of sequential data, especially textual data in natural language processing. In particular, Bidirectional LSTMs are at the heart of several neural models achieving state-of-the-art performance in a wide variety of tasks in NLP. However, BiLSTMs are known to suffer from sequential bias - the contextual representation of a token is heavily influenced by tokens close to it in a sentence. We propose a general and effective improvement to the BiLSTM model which encodes each suffix and prefix of a sequence of tokens in both forward and reverse directions. We call our model Suffix Bidirectional LSTM or SuBiLSTM. This introduces an alternate bias that favors long range dependencies. We apply SuBiLSTMs to several tasks that require sentence modeling. We demonstrate that using SuBiLSTM instead of a BiLSTM in existing models leads to improvements in performance in learning general sentence representations, text classification, textual entailment and paraphrase detection. Using SuBiLSTM we achieve new state-of-the-art results for fine-grained sentiment classification and question classification.

##### Abstract (translated by Google)
递归神经网络已经变得普遍用于计算顺序数据的表示，尤其是自然语言处理中的文本数据。特别是，双向LSTM是几个神经模型的核心，在NLP中的各种任务中实现了最先进的性能。然而，众所周知，BiLSTM会受到顺序偏差的影响 - 令牌的上下文表示受到句子中靠近它的标记的严重影响。我们提出对BiLSTM模型的一般和有效改进，该模型在前向和反向上编码一系列令牌的每个后缀和前缀。我们将模型称为后缀双向LSTM或SuBiLSTM。这引入了一种有利于长程依赖性的替代偏见。我们将SuBiLSTM应用于需要句子建模的几个任务。我们证明在现有模型中使用SuBiLSTM而不是BiLSTM可以提高学习一般句子表示，文本分类，文本蕴涵和释义检测的性能。使用SuBiLSTM，我们获得了细粒度情感分类和问题分类的最新结果。

##### URL
[http://arxiv.org/abs/1805.07340](http://arxiv.org/abs/1805.07340)

##### PDF
[http://arxiv.org/pdf/1805.07340](http://arxiv.org/pdf/1805.07340)

