---
layout: post
title: "Classification with Fairness Constraints: A Meta-Algorithm with Provable Guarantees"
date: 2018-06-15 17:45:58
categories: arXiv_AI
tags: arXiv_AI Optimization Classification
author: L. Elisa Celis, Lingxiao Huang, Vijay Keswani, Nisheeth K. Vishnoi
mathjax: true
---

* content
{:toc}

##### Abstract
Developing classification algorithms that are fair with respect to sensitive attributes of the data has become an important problem due to the growing deployment of classification algorithms in various social contexts. Several recent works have focused on fairness with respect to a specific metric, modeled the corresponding fair classification problem as a constrained optimization problem, and developed tailored algorithms to solve them. Despite this, there still remain important metrics for which we do not have fair classifiers and many of the aforementioned algorithms do not come with theoretical guarantees; perhaps because the resulting optimization problem is non-convex. The main contribution of this paper is a new meta-algorithm for classification that takes as input a large class of fairness constraints, with respect to multiple non-disjoint sensitive attributes, and which comes with provable guarantees. This is achieved by first developing a meta-algorithm for a large family of classification problems with convex constraints, and then showing that classification problems with general types of fairness constraints can be reduced to those in this family. We present empirical results that show that our algorithm can achieve near-perfect fairness with respect to various fairness metrics, and that the loss in accuracy due to the imposed fairness constraints is often small. Overall, this work unifies several prior works on fair classification, presents a practical algorithm with theoretical guarantees, and can handle fairness metrics that were previously not possible.

##### Abstract (translated by Google)
由于分类算法在各种社会环境中的部署越来越多，因此开发对数据敏感属性公平的分类算法已成为一个重要问题。最近的一些着作关注于具体度量的公平性，将相应的公平分类问题建模为约束优化问题，并开发了量身定制的算法来解决它们。尽管如此，仍然存在一些重要的指标，我们没有公平的分类器，并且许多上述算法没有提供理论保证;也许是因为最终的优化问题是非凸的。本文的主要贡献是一种新的用于分类的元算法，该算法将大量的公平约束作为输入，针对多个不相交的敏感属性，并且具有可证实的保证。这是通过首先为具有凸约束的大分类问题族开发一个元算法，然后表明一般类型的公平约束的分类问题可以减少到该族的分类问题。我们提出的实证结果表明，我们的算法可以实现关于各种公平度量的近乎完美的公平性，并且由于所施加的公平性约束导致的准确度损失通常很小。总的来说，这项工作统一了几个关于公平分类的先前工作，提出了一个具有理论保证的实用算法，并且可以处理以前不可能的公平指标。

##### URL
[http://arxiv.org/abs/1806.06055](http://arxiv.org/abs/1806.06055)

##### PDF
[http://arxiv.org/pdf/1806.06055](http://arxiv.org/pdf/1806.06055)

