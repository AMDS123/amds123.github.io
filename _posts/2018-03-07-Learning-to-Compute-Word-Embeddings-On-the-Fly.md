---
layout: post
title: "Learning to Compute Word Embeddings On the Fly"
date: 2018-03-07 16:07:10
categories: arXiv_CL
tags: arXiv_CL Embedding Language_Model
author: Dzmitry Bahdanau, Tom Bosc, Stanis&#x142;aw Jastrz&#x119;bski, Edward Grefenstette, Pascal Vincent, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Words in natural language follow a Zipfian distribution whereby some words are frequent but most are rare. Learning representations for words in the "long tail" of this distribution requires enormous amounts of data. Representations of rare words trained directly on end tasks are usually poor, requiring us to pre-train embeddings on external data, or treat all rare words as out-of-vocabulary words with a unique representation. We provide a method for predicting embeddings of rare words on the fly from small amounts of auxiliary data with a network trained end-to-end for the downstream task. We show that this improves results against baselines where embeddings are trained on the end task for reading comprehension, recognizing textual entailment and language modeling.

##### Abstract (translated by Google)
自然语言中的单词遵循Zipfian分布，因此一些词语很常见，但大多数词汇很少。在这种分配的“长尾”中学习单词的表示需要大量的数据。直接在终端任务上训练的稀有词语的表示通常很差，要求我们预先训练嵌入到外部数据中，或将所有罕见词汇用单词表达方式处理为词汇外词语。我们提供了一种方法，可以从少量的辅助数据中实时预测罕见字的嵌入，并为端下行任务提供端到端的网络训练。我们表明，这提高了对基线的结果，在这些基线中嵌入被训练在阅读理解的最终任务上，识别文本蕴涵和语言建模。

##### URL
[http://arxiv.org/abs/1706.00286](http://arxiv.org/abs/1706.00286)

##### PDF
[http://arxiv.org/pdf/1706.00286](http://arxiv.org/pdf/1706.00286)

