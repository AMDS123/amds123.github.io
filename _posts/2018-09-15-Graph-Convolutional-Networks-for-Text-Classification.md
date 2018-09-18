---
layout: post
title: "Graph Convolutional Networks for Text Classification"
date: 2018-09-15 09:13:12
categories: arXiv_AI
tags: arXiv_AI Knowledge Text_Classification Embedding CNN Classification Relation
author: Liang Yao, Chengsheng Mao, Yuan Luo
mathjax: true
---

* content
{:toc}

##### Abstract
Text Classification is an important and classical problem in natural language processing. There have been a number of studies that applied convolutional neural networks (convolution on regular grid, e.g., sequence) to classification. However, only a limited number of studies have explored the more flexible graph convolutional neural networks (e.g., convolution on non-grid, e.g., arbitrary graph) for the task. In this work, we propose to use graph convolutional networks for text classification. We build a single text graph for a corpus based on word co-occurrence and document word relations, then learn a Text Graph Convolutional Network (Text GCN) for the corpus. Our Text GCN is initialized with one-hot representation for word and document, it then jointly learns the embeddings for both words and documents, as supervised by the known class labels for documents. Our experimental results on multiple benchmark datasets demonstrate that a vanilla Text GCN without any external word embeddings or knowledge outperforms state-of-the-art methods for text classification. On the other hand, Text GCN also learns predictive word and document embeddings. In addition, experimental results show that the improvement of Text GCN over state-of-the-art comparison methods become more prominent as we lower the percentage of training data, suggesting the robustness of Text GCN to less training data in text classification.

##### Abstract (translated by Google)
文本分类是自然语言处理中的一个重要且经典的问题。已经有许多研究将卷积神经网络（常规网格上的卷积，例如序列）应用于分类。然而，仅有限数量的研究已经针对该任务探索了更灵活的图卷积神经网络（例如，非网格上的卷积，例如，任意图）。在这项工作中，我们建议使用图卷积网络进行文本分类。我们基于单词共现和文档单词关系为语料库构建单个文本图，然后学习语料库的文本图卷演网络（Text GCN）。我们的文本GCN初始化为单词和文档的单热表示，然后联合学习单词和文档的嵌入，由已知的文档类标签监督。我们在多个基准数据集上的实验结果表明，没有任何外部词嵌入或知识的vanilla Text GCN优于最先进的文本分类方法。另一方面，Text GCN还学习预测单词和文档嵌入。此外，实验结果表明，文本GCN相对于最先进的比较方法的改进变得更加突出，因为我们降低了训练数据的百分比，表明文本GCN在文本分类中减少训练数据的鲁棒性。

##### URL
[http://arxiv.org/abs/1809.05679](http://arxiv.org/abs/1809.05679)

##### PDF
[http://arxiv.org/pdf/1809.05679](http://arxiv.org/pdf/1809.05679)

