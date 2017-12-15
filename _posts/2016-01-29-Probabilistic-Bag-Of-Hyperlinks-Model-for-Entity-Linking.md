---
layout: post
title: "Probabilistic Bag-Of-Hyperlinks Model for Entity Linking"
date: 2016-01-29 19:22:44
categories: arXiv_CL
tags: arXiv_CL Summarization Inference
author: Octavian-Eugen Ganea, Marina Ganea, Aurelien Lucchi, Carsten Eickhoff, Thomas Hofmann
mathjax: true
---

* content
{:toc}

##### Abstract
Many fundamental problems in natural language processing rely on determining what entities appear in a given text. Commonly referenced as entity linking, this step is a fundamental component of many NLP tasks such as text understanding, automatic summarization, semantic search or machine translation. Name ambiguity, word polysemy, context dependencies and a heavy-tailed distribution of entities contribute to the complexity of this problem. We here propose a probabilistic approach that makes use of an effective graphical model to perform collective entity disambiguation. Input mentions (i.e.,~linkable token spans) are disambiguated jointly across an entire document by combining a document-level prior of entity co-occurrences with local information captured from mentions and their surrounding context. The model is based on simple sufficient statistics extracted from data, thus relying on few parameters to be learned. Our method does not require extensive feature engineering, nor an expensive training procedure. We use loopy belief propagation to perform approximate inference. The low complexity of our model makes this step sufficiently fast for real-time usage. We demonstrate the accuracy of our approach on a wide range of benchmark datasets, showing that it matches, and in many cases outperforms, existing state-of-the-art methods.

##### Abstract (translated by Google)
自然语言处理中的许多基本问题都依赖于确定给定文本中出现的实体。通常被称为实体链接，这一步是许多NLP任务的基本组成部分，如文本理解，自动汇总，语义搜索或机器翻译。名称歧义，单词多义性，上下文依赖性和实体的重尾分布有助于这个问题的复杂性。我们在这里提出了一个概率方法，利用一个有效的图形模型来执行集体实体消歧。输入提及（即，可链接的令牌跨度）通过将实体共现之前的文档级别与从提及及其周围环境中获取的本地信息相结合而在整个文档中联合消除歧义。该模型基于从数据中提取的简单足够的统计量，从而依靠少量参数来学习。我们的方法不需要大量的特征工程，也不需要昂贵的培训程序。我们使用loopy置信传播来进行近似推理。我们模型的低复杂性使得这个步骤足够快速的实时使用。我们在广泛的基准数据集上展示了我们的方法的准确性，表明它与现有最先进的方法相匹配，并且在许多情况下表现优于现有方法。

##### URL
[https://arxiv.org/abs/1509.02301](https://arxiv.org/abs/1509.02301)

##### PDF
[https://arxiv.org/pdf/1509.02301](https://arxiv.org/pdf/1509.02301)

