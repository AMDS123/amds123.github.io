---
layout: post
title: "Automatic Argumentative-Zoning Using Word2vec"
date: 2017-03-29 17:33:27
categories: arXiv_SD
tags: arXiv_SD Summarization Embedding Classification Language_Model
author: Haixia Liu
mathjax: true
---

* content
{:toc}

##### Abstract
In comparison with document summarization on the articles from social media and newswire, argumentative zoning (AZ) is an important task in scientific paper analysis. Traditional methodology to carry on this task relies on feature engineering from different levels. In this paper, three models of generating sentence vectors for the task of sentence classification were explored and compared. The proposed approach builds sentence representations using learned embeddings based on neural network. The learned word embeddings formed a feature space, to which the examined sentence is mapped to. Those features are input into the classifiers for supervised classification. Using 10-cross-validation scheme, evaluation was conducted on the Argumentative-Zoning (AZ) annotated articles. The results showed that simply averaging the word vectors in a sentence works better than the paragraph to vector algorithm and by integrating specific cuewords into the loss function of the neural network can improve the classification performance. In comparison with the hand-crafted features, the word2vec method won for most of the categories. However, the hand-crafted features showed their strength on classifying some of the categories.

##### Abstract (translated by Google)
与社交媒体和社交媒体文章的文献综述相比，论文分区（AZ）是科学论文分析的一项重要任务。传统的方法来执行这个任务依赖于从不同层面的特征工程。本文对三种句子分类任务生成模型进行了探索和比较。所提出的方法使用基于神经网络的学习嵌入来构建句子表示。学习的单词嵌入形成了被检查的句子被映射到的特征空间。这些特征被输入到用于监督分类的分类器中。使用10交叉验证方案，对论证分区（AZ）注释文章进行评估。结果表明，简单地平均一个句子中的单词向量，比段落对向量算法效果更好，并且通过将特定的单词集成到神经网络的损失函数中可以提高分类性能。与手工制作的功能相比，word2vec方法赢得了大多数类别。然而，手工制作的特征显示了它们在分类某些类别方面的优势。

##### URL
[https://arxiv.org/abs/1703.10152](https://arxiv.org/abs/1703.10152)

##### PDF
[https://arxiv.org/pdf/1703.10152](https://arxiv.org/pdf/1703.10152)

