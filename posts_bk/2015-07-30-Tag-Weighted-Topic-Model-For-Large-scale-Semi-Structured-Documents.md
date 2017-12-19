---
layout: post
title: "Tag-Weighted Topic Model For Large-scale Semi-Structured Documents"
date: 2015-07-30 06:44:37
categories: arXiv_CL
tags: arXiv_CL Text_Classification Inference Classification Prediction
author: Shuangyin Li, Jiefei Li, Guan Huang, Ruiyang Tan, Rong Pan
mathjax: true
---

* content
{:toc}

##### Abstract
To date, there have been massive Semi-Structured Documents (SSDs) during the evolution of the Internet. These SSDs contain both unstructured features (e.g., plain text) and metadata (e.g., tags). Most previous works focused on modeling the unstructured text, and recently, some other methods have been proposed to model the unstructured text with specific tags. To build a general model for SSDs remains an important problem in terms of both model fitness and efficiency. We propose a novel method to model the SSDs by a so-called Tag-Weighted Topic Model (TWTM). TWTM is a framework that leverages both the tags and words information, not only to learn the document-topic and topic-word distributions, but also to infer the tag-topic distributions for text mining tasks. We present an efficient variational inference method with an EM algorithm for estimating the model parameters. Meanwhile, we propose three large-scale solutions for our model under the MapReduce distributed computing platform for modeling large-scale SSDs. The experimental results show the effectiveness, efficiency and the robustness by comparing our model with the state-of-the-art methods in document modeling, tags prediction and text classification. We also show the performance of the three distributed solutions in terms of time and accuracy on document modeling.

##### Abstract (translated by Google)
迄今为止，互联网发展过程中已经出现了大量的半结构化文档（SSD）。这些SSD包含非结构化特征（例如纯文本）和元数据（例如标签）。以往的大部分工作都是针对非结构化文本进行建模，最近还提出了其他一些方法来对非结构化文本进行特定标记建模。建立SSD的通用模型仍然是模型适应性和效率方面的一个重要问题。我们提出了一种新的方法，通过所谓的标签加权主题模型（TWTM）对SSD进行建模。 TWTM是一个利用标签和单词信息的框架，不仅可以学习文档主题和主题词分布，还可以推断文本挖掘任务的标签主题分布。我们提出了一个有效的变分推理方法与EM算法估计模型参数。同时，我们在MapReduce分布式计算平台下为我们的模型提出了三个大型解决方案，用于对大型SSD进行建模。实验结果通过将我们的模型与文档建模，标签预测和文本分类中的最先进的方法进行比较来显示效果，效率和鲁棒性。我们还展示了三种分布式解决方案在文档建模方面的时间和准确性。

##### URL
[https://arxiv.org/abs/1507.08396](https://arxiv.org/abs/1507.08396)

##### PDF
[https://arxiv.org/pdf/1507.08396](https://arxiv.org/pdf/1507.08396)

