---
layout: post
title: "Expanding Abbreviations in a Strongly Inflected Language: Are Morphosyntactic Tags Sufficient?"
date: 2018-05-27 10:46:24
categories: arXiv_CL
tags: arXiv_CL Knowledge Embedding RNN Classification Prediction
author: Piotr &#x17b;elasko
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, the problem of recovery of morphological information lost in abbreviated forms is addressed with a focus on highly inflected languages. Evidence is presented that the correct inflected form of an expanded abbreviation can in many cases be deduced solely from the morphosyntactic tags of the context. The prediction model is a deep bidirectional LSTM network with tag embedding. The training and evaluation data are gathered by finding the words which could have been abbreviated and using their corresponding morphosyntactic tags as the labels, while the tags of the context words are used as the input features for classification. The network is trained on over 10 million words from the Polish Sejm Corpus and achieves 74.2% prediction accuracy on a smaller, but more general National Corpus of Polish. The analysis of errors suggests that performance in this task may improve if some prior knowledge about the abbreviated word is incorporated into the model.

##### Abstract (translated by Google)
在本文中，以简化形式丢失的形态信息恢复问题是以高度变形的语言为重点。有证据表明，扩展缩写的正确折射形式在许多情况下可以仅从上下文的形态句法标签推导出来。预测模型是具有标签嵌入的深度双向LSTM网络。训练和评估数据是通过找到可能被缩写的单词并使用其相应的形态句法标签作为标签来收集的，而上下文单词的标签被用作输入特征来进行分类。该网络接受来自波兰Sejm Corpus的超过1000万字的训练，并在较小但更普遍的波兰国家语料库上实现了74.2％的预测准确率。对错误的分析表明，如果将关于缩写词的一些先前知识并入模型中，此任务的性能可能会提高。

##### URL
[http://arxiv.org/abs/1708.05992](http://arxiv.org/abs/1708.05992)

##### PDF
[http://arxiv.org/pdf/1708.05992](http://arxiv.org/pdf/1708.05992)

