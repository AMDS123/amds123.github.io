---
layout: post
title: "Zero-shot Recognition via Semantic Embeddings and Knowledge Graphs"
date: 2018-03-21 17:52:42
categories: arXiv_CV
tags: arXiv_CV Knowledge_Graph Knowledge Embedding CNN Relation Recognition
author: Xiaolong Wang, Yufei Ye, Abhinav Gupta
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of zero-shot recognition: learning a visual classifier for a category with zero training examples, just using the word embedding of the category and its relationship to other categories, which visual data are provided. The key to dealing with the unfamiliar or novel category is to transfer knowledge obtained from familiar classes to describe the unfamiliar class. In this paper, we build upon the recently introduced Graph Convolutional Network (GCN) and propose an approach that uses both semantic embeddings and the categorical relationships to predict the classifiers. Given a learned knowledge graph (KG), our approach takes as input semantic embeddings for each node (representing visual category). After a series of graph convolutions, we predict the visual classifier for each category. During training, the visual classifiers for a few categories are given to learn the GCN parameters. At test time, these filters are used to predict the visual classifiers of unseen categories. We show that our approach is robust to noise in the KG. More importantly, our approach provides significant improvement in performance compared to the current state-of-the-art results (from 2 ~ 3% on some metrics to whopping 20% on a few).

##### Abstract (translated by Google)
我们考虑零点识别的问题：学习一个零训练样例的类别的视觉分类器，只是使用该类的词嵌入和其与其他类别的关系，提供可视化数据。处理不熟悉或新颖的类别的关键是将从熟悉的类获得的知识转移到描述不熟悉的类。在本文中，我们建立在最近引入的图形卷积网络（GCN）上，并提出了一种使用语义嵌入和分类关系来预测分类器的方法。给定学习知识图（KG），我们的方法将每个节点的输入语义嵌入（代表视觉类别）作为输入。经过一系列的图形卷积，我们预测每个类别的视觉分类器。在训练期间，给出几个类别的视觉分类器来学习GCN参数。在测试时间，这些过滤器用于预测未见类别的视觉分类器。我们证明我们的方法对于KG中的噪音是强健的。更重要的是，与目前最先进的结果相比，我们的方法在性能方面有显着的提高（从一些指标的2％到3％到少数几个达到20％）。

##### URL
[http://arxiv.org/abs/1803.08035](http://arxiv.org/abs/1803.08035)

##### PDF
[http://arxiv.org/pdf/1803.08035](http://arxiv.org/pdf/1803.08035)

