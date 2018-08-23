---
layout: post
title: "Neural Named Entity Recognition from Subword Units"
date: 2018-08-22 13:56:51
categories: arXiv_CL
tags: arXiv_CL Embedding RNN Recognition
author: Abdalghani Abujabal, Judith Gaspers
mathjax: true
---

* content
{:toc}

##### Abstract
Named entity recognition (NER) is a vital task in language technology. Existing neural models for NER rely mostly on dedicated word-level representations, which suffer from two main shortcomings: 1) the vocabulary size is large, yielding large memory requirements and training time, and 2) they cannot learn morphological representations. We adopt a neural solution based on bidirectional LSTMs and conditional random fields, where we rely on subword units, namely characters, phonemes, and bytes, to remedy the above shortcomings. We conducted experiments on a large dataset covering four languages with up to 5.5M utterances per language. Our experiments show that 1) with increasing training data, performance of models trained solely on subword units becomes closer to that of models with dedicated word-level embeddings (91.35 vs 93.92 F1 for English), while using a much smaller vocabulary size (332 vs 74K), 2) subword units enhance models with dedicated word-level embeddings, and 3) combining different subword units improves performance.

##### Abstract (translated by Google)
命名实体识别（NER）是语言技术中的一项重要任务。用于NER的现有神经模型主要依赖于专用的单词级表示，其具有两个主要缺点：1）词汇量大，产生大的记忆要求和训练时间，以及2）他们不能学习形态表示。我们采用基于双向LSTM和条件随机场的神经解决方案，其中我们依赖于子字单元，即字符，音素和字节，来弥补上述缺点。我们在一个涵盖四种语言的大型数据集上进行了实验，每种语言的语音高达5.5M。我们的实验表明：1）随着训练数据的增加，仅在子词单元上训练的模型的性能变得更接近具有专用词级嵌入的模型（英语为91.35 vs 93.92 F1），同时使用更小的词汇量（332 vs 74K），2）子字单元增强了具有专用字级嵌入的模型，以及3）组合不同的子字单元提高了性能。

##### URL
[http://arxiv.org/abs/1808.07364](http://arxiv.org/abs/1808.07364)

##### PDF
[http://arxiv.org/pdf/1808.07364](http://arxiv.org/pdf/1808.07364)

