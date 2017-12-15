---
layout: post
title: "Fine-Grained Entity Type Classification by Jointly Learning Representations and Label Embeddings"
date: 2017-02-22 08:59:37
categories: arXiv_SD
tags: arXiv_SD Knowledge Embedding Classification
author: Abhishek, Ashish Anand, Amit Awekar
mathjax: true
---

* content
{:toc}

##### Abstract
Fine-grained entity type classification (FETC) is the task of classifying an entity mention to a broad set of types. Distant supervision paradigm is extensively used to generate training data for this task. However, generated training data assigns same set of labels to every mention of an entity without considering its local context. Existing FETC systems have two major drawbacks: assuming training data to be noise free and use of hand crafted features. Our work overcomes both drawbacks. We propose a neural network model that jointly learns entity mentions and their context representation to eliminate use of hand crafted features. Our model treats training data as noisy and uses non-parametric variant of hinge loss function. Experiments show that the proposed model outperforms previous state-of-the-art methods on two publicly available datasets, namely FIGER (GOLD) and BBN with an average relative improvement of 2.69% in micro-F1 score. Knowledge learnt by our model on one dataset can be transferred to other datasets while using same model or other FETC systems. These approaches of transferring knowledge further improve the performance of respective models.

##### Abstract (translated by Google)
细粒度的实体类型分类（FETC）是将一个实体分类为一大类类型的任务。远程监督范式被广泛用于为这项任务生成训练数据。然而，生成的训练数据为每个提到的实体分配相同的标签集，而不考虑其本地情况。现有的FETC系统有两个主要的缺点：假设训练数据是无噪音的并且使用手工制作的特征。我们的工作克服了两个缺点。我们提出了一个神经网络模型，共同学习实体提及及其上下文表示，以消除使用手工制作的特征。我们的模型将训练数据视为噪声，并使用铰链损失函数的非参数变体。实验表明，所提出的模型在两个公开可用的数据集（即FIGER（GOLD）和BBN）上优于以前的现有技术方法，在微F1成绩中平均相对改善2.69％。通过我们的模型在一个数据集上学习的知识可以在使用相同模型或其他FETC系统的同时传输到其他数据集。这些传递知识的方法进一步提高了各个模型的性能。

##### URL
[https://arxiv.org/abs/1702.06709](https://arxiv.org/abs/1702.06709)

##### PDF
[https://arxiv.org/pdf/1702.06709](https://arxiv.org/pdf/1702.06709)

