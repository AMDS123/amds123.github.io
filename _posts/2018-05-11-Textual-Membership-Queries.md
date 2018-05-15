---
layout: post
title: "Textual Membership Queries"
date: 2018-05-11 22:40:59
categories: arXiv_CL
tags: arXiv_CL Knowledge Text_Classification Classification Language_Model
author: Jonathan Zarecki, Shaul Markovitch
mathjax: true
---

* content
{:toc}

##### Abstract
Human labeling of textual data can be very time-consuming and expensive, yet it is critical for the success of an automatic text classification system. In order to minimize human labeling efforts, we propose a novel active learning (AL) solution, that does not rely on existing sources of unlabeled data. It uses a small amount of labeled data as the core set for the synthesis of useful membership queries (MQs) - unlabeled instances synthesized by an algorithm for human labeling. Our solution uses modification operators, functions from the instance space to the instance space that change the input to some extent. We apply the operators on the core set, thus creating a set of new membership queries. Using this framework, we look at the instance space as a search space and apply search algorithms in order to create desirable MQs. We implement this framework in the textual domain. The implementation includes using methods such as WordNet and Word2vec, for replacing text fragments from a given sentence with semantically related ones. We test our framework on several text classification tasks and show improved classifier performance as more MQs are labeled and incorporated into the training set. To the best of our knowledge, this is the first work on membership queries in the textual domain.

##### Abstract (translated by Google)
文本数据的人类标记可能非常耗时且昂贵，但它对于自动文本分类系统的成功至关重要。为了最大限度地减少人类标记工作，我们提出了一种新颖的主动学习（AL）解决方案，它不依赖于现有的未标记数据来源。它使用少量标记数据作为合成有用成员资格查询（MQ）的核心集合 - 通过人类标记算法合成的未标记实例。我们的解决方案使用修改操作符，从实例空间到实例空间的功能，这些功能在一定程度上改变了输入。我们将这些操作符应用于核心集，从而创建一组新的成员查询。使用这个框架，我们将实例空间看作搜索空间并应用搜索算法来创建所需的MQ。我们在文本领域实施这个框架。该实现包括使用诸如WordNet和Word2vec等方法来替换来自给定语句的文本片段和语义相关的文本片段。我们在几个文本分类任务上测试我们的框架，并且显示更好的分类器性能，因为更多的MQ被标记并且并入到训练集中。据我们所知，这是关于文本域中的成员查询的第一项工作。

##### URL
[https://arxiv.org/abs/1805.04609](https://arxiv.org/abs/1805.04609)

##### PDF
[https://arxiv.org/pdf/1805.04609](https://arxiv.org/pdf/1805.04609)

