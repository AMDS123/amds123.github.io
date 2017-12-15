---
layout: post
title: "Mapping Unseen Words to Task-Trained Embedding Spaces"
date: 2016-06-23 06:24:18
categories: arXiv_CL
tags: arXiv_CL Sentiment Embedding
author: Pranava Swaroop Madhyastha, Mohit Bansal, Kevin Gimpel, Karen Livescu
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the supervised training setting in which we learn task-specific word embeddings. We assume that we start with initial embeddings learned from unlabelled data and update them to learn task-specific embeddings for words in the supervised training data. However, for new words in the test set, we must use either their initial embeddings or a single unknown embedding, which often leads to errors. We address this by learning a neural network to map from initial embeddings to the task-specific embedding space, via a multi-loss objective function. The technique is general, but here we demonstrate its use for improved dependency parsing (especially for sentences with out-of-vocabulary words), as well as for downstream improvements on sentiment analysis.

##### Abstract (translated by Google)
我们考虑监督训练设置，在其中我们学习任务特定的词嵌入。我们假设我们从未标记数据中学习的初始嵌入开始，并更新它们以在监督训练数据中学习单词的任务特定嵌入。但是，对于测试集中的新单词，我们必须使用它们的初始嵌入或单个未知嵌入，这往往导致错误。我们通过学习一个神经网络来解决这个问题，通过多损失目标函数从最初的嵌入映射到任务特定的嵌入空间。这种技术是一般性的，但是我们在这里展示了它用于改进依赖关系解析（特别是对于词汇超出单词的句子），以及对情感分析的下游改进。

##### URL
[https://arxiv.org/abs/1510.02387](https://arxiv.org/abs/1510.02387)

##### PDF
[https://arxiv.org/pdf/1510.02387](https://arxiv.org/pdf/1510.02387)

