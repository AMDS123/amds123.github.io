---
layout: post
title: "Learning to Compute Word Embeddings On the Fly"
date: 2017-06-05 20:18:27
categories: arXiv_CL
tags: arXiv_CL Embedding Language_Model
author: Dzmitry Bahdanau, Tom Bosc, Stanisław Jastrzębski, Edward Grefenstette, Pascal Vincent, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Words in natural language follow a Zipfian distribution whereby some words are frequent but most are rare. Learning representations for words in the "long tail" of this distribution requires enormous amounts of data. Representations of rare words trained directly on end-tasks are usually poor, requiring us to pre-train embeddings on external data, or treat all rare words as out-of-vocabulary words with a unique representation. We provide a method for predicting embeddings of rare words on the fly from small amounts of auxiliary data with a network trained against the end task. We show that this improves results against baselines where embeddings are trained on the end task in a reading comprehension task, a recognizing textual entailment task, and in language modelling.

##### Abstract (translated by Google)
自然语言中的单词遵循Zipfian分布，因此一些单词频繁出现，但大多数是罕见的。在这种分配的“长尾”中学习单词的表示需要大量的数据。直接在终端任务上训练的稀有词语的表示通常很差，要求我们预先训练嵌入到外部数据中，或者将所有稀有词汇用单词表示方式处理为词汇外词汇。我们提供了一种方法来预测从少量的辅助数据中随机运行一个网络训练罕见词的嵌入。我们表明，这改善了对基线的结果，这些基线是在阅读理解任务的最终任务上进行嵌入训练，识别文本包含任务以及在语言建模中。

##### URL
[https://arxiv.org/abs/1706.00286](https://arxiv.org/abs/1706.00286)

##### PDF
[https://arxiv.org/pdf/1706.00286](https://arxiv.org/pdf/1706.00286)

