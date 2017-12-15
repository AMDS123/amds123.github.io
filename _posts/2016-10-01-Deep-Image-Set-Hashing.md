---
layout: post
title: "Deep Image Set Hashing"
date: 2016-10-01 02:14:51
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Knowledge Embedding Relation
author: Jie Feng, Svebor Karaman, I-Hong Jhuo, Shih-Fu Chang
mathjax: true
---

* content
{:toc}

##### Abstract
In applications involving matching of image sets, the information from multiple images must be effectively exploited to represent each set. State-of-the-art methods use probabilistic distribution or subspace to model a set and use specific distance measure to compare two sets. These methods are slow to compute and not compact to use in a large scale scenario. Learning-based hashing is often used in large scale image retrieval as they provide a compact representation of each sample and the Hamming distance can be used to efficiently compare two samples. However, most hashing methods encode each image separately and discard knowledge that multiple images in the same set represent the same object or person. We investigate the set hashing problem by combining both set representation and hashing in a single deep neural network. An image set is first passed to a CNN module to extract image features, then these features are aggregated using two types of set feature to capture both set specific and database-wide distribution information. The computed set feature is then fed into a multilayer perceptron to learn a compact binary embedding. Triplet loss is used to train the network by forming set similarity relations using class labels. We extensively evaluate our approach on datasets used for image matching and show highly competitive performance compared to state-of-the-art methods.

##### Abstract (translated by Google)
在涉及图像集合匹配的应用中，必须有效利用来自多个图像的信息来表示每个集合。最先进的方法使用概率分布或子空间来对一个集合建模，并使用特定的距离度量来比较两个集合。这些方法计算速度慢，不适合在大规模情况下使用。基于学习的散列经常用于大规模图像检索，因为它们提供每个样本的紧凑表示，并且可以使用汉明距离来有效地比较两个样本。然而，大多数哈希方法分别对每个图像进行编码，并丢弃关于同一集合中的多个图像表示相同的对象或人的知识。我们通过在单个深度神经网络中结合集合表示和散列来研究集合哈希问题。图像集首先传递给CNN模块以提取图像特征，然后使用两种类型的特征集合这些特征以捕获集合特定和全数据库范围的分布信息。然后将所计算的集合特征馈送到多层感知器中以学习紧凑二进制嵌入。三元组丢失用于通过使用类别标签形成集合相似性关系来训练网络。我们广泛地评估了我们用于图像匹配的数据集方法，并且与最先进的方法相比显示出极具竞争力的性能。

##### URL
[https://arxiv.org/abs/1606.05381](https://arxiv.org/abs/1606.05381)

##### PDF
[https://arxiv.org/pdf/1606.05381](https://arxiv.org/pdf/1606.05381)

