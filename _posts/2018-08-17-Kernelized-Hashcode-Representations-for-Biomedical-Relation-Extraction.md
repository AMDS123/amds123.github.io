---
layout: post
title: "Kernelized Hashcode Representations for Biomedical Relation Extraction"
date: 2018-08-17 16:28:56
categories: arXiv_CL
tags: arXiv_CL Relation_Extraction Classification Relation
author: Sahil Garg, Aram Galstyan, Greg Ver Steeg, Irina Rish, Guillermo Cecchi, Shuyang Gao
mathjax: true
---

* content
{:toc}

##### Abstract
Kernel methods have produced state-of-the-art results for a number of NLP tasks such as relation extraction, but suffer from poor scalability due to the high cost of computing kernel similarities between discrete natural language structures. A recently proposed technique, kernelized locality-sensitive hashing (KLSH), can significantly reduce the computational cost, but is only applicable to classifiers operating on kNN graphs. Here we propose to use random subspaces of KLSH codes for efficiently constructing an explicit representation of NLP structures suitable for general classification methods. Further, we propose an approach for optimizing the KLSH model for classification problems by maximizing a variational lower bound on mutual information between the KLSH codes (feature vectors) and the class labels. We evaluate the proposed approach on biomedical relation extraction datasets, and observe significant and robust improvements in accuracy w.r.t. state-of-the-art classifiers, along with drastic (orders-of-magnitude) speedup compared to conventional kernel methods.

##### Abstract (translated by Google)
内核方法已经为许多NLP任务（例如关系提取）产生了最先进的结果，但由于计算离散自然语言结构之间的内核相似性的高成本而导致可扩展性差。最近提出的技术，核化局部敏感散列（KLSH），可以显着降低计算成本，但仅适用于在kNN图上运行的分类器。这里我们建议使用KLSH代码的随机子空间来有效地构造适用于一般分类方法的NLP结构的显式表示。此外，我们提出了一种通过最大化KLSH代码（特征向量）和类标签之间的互信息的变化下界来优化分类问题的KLSH模型的方法。我们评估了生物医学关系提取数据集的拟议方法，并观察到精确度的显着和稳健的改进。与传统的内核方法相比，最先进的分类器，以及极大的（数量级）加速。

##### URL
[http://arxiv.org/abs/1711.04044](http://arxiv.org/abs/1711.04044)

##### PDF
[http://arxiv.org/pdf/1711.04044](http://arxiv.org/pdf/1711.04044)

