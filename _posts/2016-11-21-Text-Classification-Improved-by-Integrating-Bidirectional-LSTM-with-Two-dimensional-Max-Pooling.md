---
layout: post
title: "Text Classification Improved by Integrating Bidirectional LSTM with Two-dimensional Max Pooling"
date: 2016-11-21 03:26:29
categories: arXiv_CL
tags: arXiv_CL Sentiment Attention Text_Classification RNN Classification
author: Peng Zhou, Zhenyu Qi, Suncong Zheng, Jiaming Xu, Hongyun Bao, Bo Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent Neural Network (RNN) is one of the most popular architectures used in Natural Language Processsing (NLP) tasks because its recurrent structure is very suitable to process variable-length text. RNN can utilize distributed representations of words by first converting the tokens comprising each text into vectors, which form a matrix. And this matrix includes two dimensions: the time-step dimension and the feature vector dimension. Then most existing models usually utilize one-dimensional (1D) max pooling operation or attention-based operation only on the time-step dimension to obtain a fixed-length vector. However, the features on the feature vector dimension are not mutually independent, and simply applying 1D pooling operation over the time-step dimension independently may destroy the structure of the feature representation. On the other hand, applying two-dimensional (2D) pooling operation over the two dimensions may sample more meaningful features for sequence modeling tasks. To integrate the features on both dimensions of the matrix, this paper explores applying 2D max pooling operation to obtain a fixed-length representation of the text. This paper also utilizes 2D convolution to sample more meaningful information of the matrix. Experiments are conducted on six text classification tasks, including sentiment analysis, question classification, subjectivity classification and newsgroup classification. Compared with the state-of-the-art models, the proposed models achieve excellent performance on 4 out of 6 tasks. Specifically, one of the proposed models achieves highest accuracy on Stanford Sentiment Treebank binary classification and fine-grained classification tasks.

##### Abstract (translated by Google)
递归神经网络（RNN）是自然语言处理（NLP）任务中最常用的体系结构之一，因为它的递归结构非常适合处理可变长度的文本。 RNN可以通过首先将包括每个文本的令牌转换成向量形成矩阵来利用单词的分布式表示。这个矩阵包括两个维度：时间步长维度和特征向量维度。然后，大多数现有的模型通常只利用一维（1D）最大池操作或基于注意的操作来获得一个固定长度的向量。然而，特征向量维度上的特征不是相互独立的，单独在时间步长维度上单独应用1D池操作可能会破坏特征表示的结构。另一方面，在二维上应用二维（2D）池操作可以为序列建模任务采样更有意义的特征。为了将这些特征集成到矩阵的两个维度上，本文探索应用2D最大池操作来获得文本的固定长度表示。本文还利用二维卷积来对矩阵的更有意义的信息进行采样。实验分六个文本分类任务，包括情感分析，问题分类，主观性分类和新闻组分类。与最先进的模型相比，所提出的模型在6个任务中的4个上实现了优异的性能。具体而言，所提出的模型之一在斯坦福情绪树库二进制分类和细粒度分类任务上达到最高准确度。

##### URL
[https://arxiv.org/abs/1611.06639](https://arxiv.org/abs/1611.06639)

##### PDF
[https://arxiv.org/pdf/1611.06639](https://arxiv.org/pdf/1611.06639)

