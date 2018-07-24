---
layout: post
title: "Domain Generalization via Conditional Invariant Representation"
date: 2018-07-23 08:33:46
categories: arXiv_CV
tags: arXiv_CV Knowledge Relation
author: Ya Li, Mingming Gong, Xinmei Tian, Tongliang Liu, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Domain generalization aims to apply knowledge gained from multiple labeled source domains to unseen target domains. The main difficulty comes from the dataset bias: training data and test data have different distributions, and the training set contains heterogeneous samples from different distributions. Let $X$ denote the features, and $Y$ be the class labels. Existing domain generalization methods address the dataset bias problem by learning a domain-invariant representation $h(X)$ that has the same marginal distribution $\mathbb{P}(h(X))$ across multiple source domains. The functional relationship encoded in $\mathbb{P}(Y|X)$ is usually assumed to be stable across domains such that $\mathbb{P}(Y|h(X))$ is also invariant. However, it is unclear whether this assumption holds in practical problems. In this paper, we consider the general situation where both $\mathbb{P}(X)$ and $\mathbb{P}(Y|X)$ can change across all domains. We propose to learn a feature representation which has domain-invariant class conditional distributions $\mathbb{P}(h(X)|Y)$. With the conditional invariant representation, the invariance of the joint distribution $\mathbb{P}(h(X),Y)$ can be guaranteed if the class prior $\mathbb{P}(Y)$ does not change across training and test domains. Extensive experiments on both synthetic and real data demonstrate the effectiveness of the proposed method.

##### Abstract (translated by Google)
域概括旨在将从多个标记源域获得的知识应用于看不见的目标域。主要困难来自数据集偏差：训练数据和测试数据具有不同的分布，训练集包含来自不同分布的异构样本。让$ X $表示功能，$ Y $表示类标签。现有的域泛化方法通过学习跨多个源域具有相同边际分布$ \ mathbb {P}（h（X））$的域不变表示$ h（X）$来解决数据集偏差问题。在$ \ mathbb {P}（Y | X）$中编码的函数关系通常被认为在域之间是稳定的，因此$ \ mathbb {P}（Y | h（X））$也是不变的。但是，目前还不清楚这种假设是否适用于实际问题。在本文中，我们考虑了一般情况，其中$ \ mathbb {P}（X）$和$ \ mathbb {P}（Y | X）$可以在所有域中发生变化。我们建议学习一个具有域不变类条件分布的特征表示$ \ mathbb {P}（h（X）| Y）$。使用条件不变表示，如果前一个$ \ mathbb {P}（Y）$的类在训练中没有变化，则可以保证联合分布$ \ mathbb {P}（h（X），Y）$的不变性。测试域。对合成数据和实际数据的广泛实验证明了所提出方法的有效性。

##### URL
[http://arxiv.org/abs/1807.08479](http://arxiv.org/abs/1807.08479)

##### PDF
[http://arxiv.org/pdf/1807.08479](http://arxiv.org/pdf/1807.08479)

