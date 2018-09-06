---
layout: post
title: "Utilizing Character and Word Embeddings for Text Normalization with Sequence-to-Sequence Models"
date: 2018-09-05 16:44:04
categories: arXiv_CL
tags: arXiv_CL Attention Embedding
author: Daniel Watson, Nasser Zalmout, Nizar Habash
mathjax: true
---

* content
{:toc}

##### Abstract
Text normalization is an important enabling technology for several NLP tasks. Recently, neural-network-based approaches have outperformed well-established models in this task. However, in languages other than English, there has been little exploration in this direction. Both the scarcity of annotated data and the complexity of the language increase the difficulty of the problem. To address these challenges, we use a sequence-to-sequence model with character-based attention, which in addition to its self-learned character embeddings, uses word embeddings pre-trained with an approach that also models subword information. This provides the neural model with access to more linguistic information especially suitable for text normalization, without large parallel corpora. We show that providing the model with word-level features bridges the gap for the neural network approach to achieve a state-of-the-art F1 score on a standard Arabic language correction shared task dataset.

##### Abstract (translated by Google)
文本规范化是几个NLP任务的重要支持技术。最近，基于神经网络的方法在这项任务中的表现优于完善的模型。但是，在英语以外的语言中，这方面的探索很少。注释数据的稀缺性和语言的复杂性都增加了问题的难度。为了解决这些挑战，我们使用具有基于字符的注意力的序列到序列模型，除了其自学习字符嵌入之外，还使用预先训练的字嵌入以及对子字信息进行建模的方法。这为神经模型提供了更多的语言信息，特别适用于文本规范化，没有大型并行语料库。我们表明，为模型提供单词级特征弥补了神经网络方法的空白，以在标准阿拉伯语语言修正共享任务数据集上实现最先进的F1分数。

##### URL
[http://arxiv.org/abs/1809.01534](http://arxiv.org/abs/1809.01534)

##### PDF
[http://arxiv.org/pdf/1809.01534](http://arxiv.org/pdf/1809.01534)

