---
layout: post
title: "Constructing Datasets for Multi-hop Reading Comprehension Across Documents"
date: 2018-06-11 17:08:20
categories: arXiv_AI
tags: arXiv_AI Inference
author: Johannes Welbl, Pontus Stenetorp, Sebastian Riedel
mathjax: true
---

* content
{:toc}

##### Abstract
Most Reading Comprehension methods limit themselves to queries which can be answered using a single sentence, paragraph, or document. Enabling models to combine disjoint pieces of textual evidence would extend the scope of machine comprehension methods, but currently there exist no resources to train and test this capability. We propose a novel task to encourage the development of models for text understanding across multiple documents and to investigate the limits of existing methods. In our task, a model learns to seek and combine evidence - effectively performing multi-hop (alias multi-step) inference. We devise a methodology to produce datasets for this task, given a collection of query-answer pairs and thematically linked documents. Two datasets from different domains are induced, and we identify potential pitfalls and devise circumvention strategies. We evaluate two previously proposed competitive models and find that one can integrate information across documents. However, both models struggle to select relevant information, as providing documents guaranteed to be relevant greatly improves their performance. While the models outperform several strong baselines, their best accuracy reaches 42.9% compared to human performance at 74.0% - leaving ample room for improvement.

##### Abstract (translated by Google)
大多数阅读理解方法将自己限制为可以使用单个句子，段落或文档来回答的查询。使模型能够结合不相关的文本证据将扩展机器理解方法的范围，但是目前还没有资源来训练和测试这种能力。我们提出了一项新的任务，鼓励开发跨多个文档的文本理解模型，并调查现有方法的局限性。在我们的任务中，模型学习寻找并合并证据 - 有效地执行多跳（别名多步）推理。我们设计了一个方法来产生这个任务的数据集，给定一组查询 - 答案对和主题链接的文档。诱导来自不同领域的两个数据集，并且找出潜在的陷阱并设计规避策略。我们评估两个以前提出的竞争模型，并发现可以整合文档中的信息。然而，这两种模式都难以选择相关信息，因为提供相关文件可以大大提高他们的表现。虽然这些模型的性能超过了几个强大的基线，但其最高准确度达到了42.9％，而人的绩效却达到了74.0％，这为我们留下了很大的改进空间。

##### URL
[http://arxiv.org/abs/1710.06481](http://arxiv.org/abs/1710.06481)

##### PDF
[http://arxiv.org/pdf/1710.06481](http://arxiv.org/pdf/1710.06481)

