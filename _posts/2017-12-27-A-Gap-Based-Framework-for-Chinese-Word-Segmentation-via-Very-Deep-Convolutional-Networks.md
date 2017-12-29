---
layout: post
title: "A Gap-Based Framework for Chinese Word Segmentation via Very Deep Convolutional Networks"
date: 2017-12-27 06:44:02
categories: arXiv_CL
tags: arXiv_CL Segmentation CNN
author: Zhiqing Sun, Gehui Shen, Zhihong Deng
mathjax: true
---

* content
{:toc}

##### Abstract
Most previous approaches to Chinese word segmentation can be roughly classified into character-based and word-based methods. The former regards this task as a sequence-labeling problem, while the latter directly segments character sequence into words. However, if we consider segmenting a given sentence, the most intuitive idea is to predict whether to segment for each gap between two consecutive characters, which in comparison makes previous approaches seem too complex. Therefore, in this paper, we propose a gap-based framework to implement this intuitive idea. Moreover, very deep convolutional neural networks, namely, ResNets and DenseNets, are exploited in our experiments. Results show that our approach outperforms the best character-based and word-based methods on 5 benchmarks, without any further post-processing module (e.g. Conditional Random Fields) nor beam search.

##### Abstract (translated by Google)
大多数以前的中文分词方法大致可以分为基于字符和基于字的方法。前者认为这个任务是一个序列标签问题，而后者直接将字符序列分割成单词。然而，如果我们考虑分割一个给定的句子，最直观的想法是预测是否分割两个连续字符之间的每个差距，相比之下，以前的方法看起来太复杂了。因此，在本文中，我们提出了一个基于差距的框架来实现这个直观的想法。此外，在我们的实验中，深度卷积神经网络，即ResNets和DenseNets被利用。结果表明，我们的方法在5个基准测试中胜过最佳的基于字符的和基于字的方法，没有任何进一步的后处理模块（例如，条件随机场）或波束搜索。

##### URL
[http://arxiv.org/abs/1712.09509](http://arxiv.org/abs/1712.09509)

##### PDF
[http://arxiv.org/pdf/1712.09509](http://arxiv.org/pdf/1712.09509)

