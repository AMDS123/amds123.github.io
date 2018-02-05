---
layout: post
title: "Efficient Representation for Natural Language Processing via Kernelized Hashcodes"
date: 2018-02-01 23:10:27
categories: arXiv_CL
tags: arXiv_CL Classification
author: Sahil Garg, Aram Galstyan, Greg Ver Steeg, Irina Rish, Guillermo Cecchi, Shuyang Gao
mathjax: true
---

* content
{:toc}

##### Abstract
Kernel methods have been used widely in a number of tasks, but have had limited success in Natural Language Processing (NLP) due to high cost of computing kernel similarities between discrete natural language structures. A recently proposed technique, Kernelized Locality Sensitive Hashing (KLSH), can significantly reduce the computational cost, but is only applicable to classifiers operating on kNN graphs. Here we propose to use random subspaces of KLSH codes for efficiently constructing explicit representation of natural language structures suitable for general classification methods. Further, we propose an approach for optimizing a KLSH model for classification problems, by maximizing a variational lower bound on the mutual information between the KLSH codes (feature vectors) and the class labels. We apply the proposed approach to a biomedical information extraction task, and observe robust improvements in accuracy, along with significant speedup compared to conventional kernel methods.

##### Abstract (translated by Google)
内核方法已经被广泛用于许多任务，但是在自然语言处理（NLP）方面的成功有限，因为计算离散自然语言结构之间的内核相似性成本很高。最近提出的核心局部敏感散列技术（KLSH）可以显着降低计算成本，但是仅适用于在kNN图上运行的分类器。这里我们建议使用KLSH码的随机子空间来有效地构造适用于一般分类方法的自然语言结构的显式表示。进一步，我们提出了一种通过最大化KLSH码（特征向量）和类别标签之间的互信息的变差下限来优化用于分类问题的KLSH模型的方法。我们将所提出的方法应用于生物医学信息提取任务，并且与传统的核心方法相比，观察到准确性的显着提高以及显着的加速。

##### URL
[http://arxiv.org/abs/1711.04044](http://arxiv.org/abs/1711.04044)

##### PDF
[http://arxiv.org/pdf/1711.04044](http://arxiv.org/pdf/1711.04044)

