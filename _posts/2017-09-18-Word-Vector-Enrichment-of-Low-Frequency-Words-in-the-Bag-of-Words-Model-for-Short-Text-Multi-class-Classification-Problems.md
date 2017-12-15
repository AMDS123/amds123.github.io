---
layout: post
title: "Word Vector Enrichment of Low Frequency Words in the Bag-of-Words Model for Short Text Multi-class Classification Problems"
date: 2017-09-18 05:00:34
categories: arXiv_CL
tags: arXiv_CL Sparse Text_Classification Classification Prediction
author: Bradford Heap, Michael Bain, Wayne Wobcke, Alfred Krzywicki, Susanne Schmeidl
mathjax: true
---

* content
{:toc}

##### Abstract
The bag-of-words model is a standard representation of text for many linear classifier learners. In many problem domains, linear classifiers are preferred over more complex models due to their efficiency, robustness and interpretability, and the bag-of-words text representation can capture sufficient information for linear classifiers to make highly accurate predictions. However in settings where there is a large vocabulary, large variance in the frequency of terms in the training corpus, many classes and very short text (e.g., single sentences or document titles) the bag-of-words representation becomes extremely sparse, and this can reduce the accuracy of classifiers. A particular issue in such settings is that short texts tend to contain infrequently occurring or rare terms which lack class-conditional evidence. In this work we introduce a method for enriching the bag-of-words model by complementing such rare term information with related terms from both general and domain-specific Word Vector models. By reducing sparseness in the bag-of-words models, our enrichment approach achieves improved classification over several baseline classifiers in a variety of text classification problems. Our approach is also efficient because it requires no change to the linear classifier before or during training, since bag-of-words enrichment applies only to text being classified.

##### Abstract (translated by Google)
词袋模型是许多线性分类器学习者的文本的标准表示。在许多问题领域中，由于线性分类器的效率，鲁棒性和可解释性，线性分类器比较复杂的模型更受青睐，并且袋子文本表示可以捕获足够的信息以用于线性分类器以进行高度准确的预测。然而，在词汇量大，训练语料库中词项频率差异很大的情况下，许多类别和非常短的文本（例如，单个句子或文件标题）词袋表示变得非常稀疏，可以降低分类器的准确性。在这样的背景下，一个特定的问题是短文本往往包含不经常出现的或罕见的条件，缺乏类别条件的证据。在这项工作中，我们介绍一种方法来丰富词袋模型，通过补充这些罕见的词信息与相关术语来自通用和特定领域的词向量模型。通过减少词袋模型中的稀疏性，我们的浓缩方法在各种文本分类问题中实现了对几个基线分类器的改进的分类。我们的方法也是有效的，因为它不需要在训练之前或期间对线性分类器进行改变，因为词袋丰富仅适用于被分类的文本。

##### URL
[https://arxiv.org/abs/1709.05778](https://arxiv.org/abs/1709.05778)

##### PDF
[https://arxiv.org/pdf/1709.05778](https://arxiv.org/pdf/1709.05778)

