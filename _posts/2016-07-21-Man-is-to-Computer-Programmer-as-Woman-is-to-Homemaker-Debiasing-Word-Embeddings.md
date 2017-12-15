---
layout: post
title: "Man is to Computer Programmer as Woman is to Homemaker? Debiasing Word Embeddings"
date: 2016-07-21 22:26:20
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Tolga Bolukbasi, Kai-Wei Chang, James Zou, Venkatesh Saligrama, Adam Kalai
mathjax: true
---

* content
{:toc}

##### Abstract
The blind application of machine learning runs the risk of amplifying biases present in data. Such a danger is facing us with word embedding, a popular framework to represent text data as vectors which has been used in many machine learning and natural language processing tasks. We show that even word embeddings trained on Google News articles exhibit female/male gender stereotypes to a disturbing extent. This raises concerns because their widespread use, as we describe, often tends to amplify these biases. Geometrically, gender bias is first shown to be captured by a direction in the word embedding. Second, gender neutral words are shown to be linearly separable from gender definition words in the word embedding. Using these properties, we provide a methodology for modifying an embedding to remove gender stereotypes, such as the association between between the words receptionist and female, while maintaining desired associations such as between the words queen and female. We define metrics to quantify both direct and indirect gender biases in embeddings, and develop algorithms to "debias" the embedding. Using crowd-worker evaluation as well as standard benchmarks, we empirically demonstrate that our algorithms significantly reduce gender bias in embeddings while preserving the its useful properties such as the ability to cluster related concepts and to solve analogy tasks. The resulting embeddings can be used in applications without amplifying gender bias.

##### Abstract (translated by Google)
机器学习的盲目应用会增加数据中存在的偏差。文字嵌入是一种流行的框架，它将文本数据表示为向量，这已经被用于许多机器学习和自然语言处理任务中，这样的危险正在面临着我们。我们发现即使是在Google新闻文章上训练的文字嵌入，也会令人不安的程度上表现出女性/男性的性别刻板印象。这引起了人们的担忧，因为正如我们所描述的那样，它们的广泛使用往往会放大这些偏见。在几何学上，性别偏见首先显示为嵌入这个词的方向。其次，性别中性词在嵌入词中表现为与性别定义词可线性分离。通过使用这些属性，我们提供了一种修改嵌入的方法，以消除性别刻板印象，例如在接待员和女性之间的关联，同时保持诸如女王之间和女性之间的期望关联。我们定义度量来量化嵌入中的直接和间接性别偏见，并开发算法来“嵌入”嵌入。使用人群工作者评估以及标准基准测试中，我们经验证明，我们的算法显著减少的性别偏见的嵌入，同时保留其有用的特性，如集群相关的概念和解决类比任务的能力。由此产生的嵌入可以用于应用而不会放大性别偏见。

##### URL
[https://arxiv.org/abs/1607.06520](https://arxiv.org/abs/1607.06520)

##### PDF
[https://arxiv.org/pdf/1607.06520](https://arxiv.org/pdf/1607.06520)

