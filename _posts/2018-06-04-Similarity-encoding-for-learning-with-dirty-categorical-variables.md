---
layout: post
title: "Similarity encoding for learning with dirty categorical variables"
date: 2018-06-04 06:46:22
categories: arXiv_AI
tags: arXiv_AI Prediction Recommendation
author: Patricio Cerda (PARIETAL), Ga&#xeb;l Varoquaux (PARIETAL), Bal&#xe1;zs K&#xe9;gl (LAL, CNRS)
mathjax: true
---

* content
{:toc}

##### Abstract
For statistical learning, categorical variables in a table are usually considered as discrete entities and encoded separately to feature vectors, e.g., with one-hot encoding. "Dirty" non-curated data gives rise to categorical variables with a very high cardinality but redundancy: several categories reflect the same entity. In databases, this issue is typically solved with a deduplication step. We show that a simple approach that exposes the redundancy to the learning algorithm brings significant gains. We study a generalization of one-hot encoding, similarity encoding, that builds feature vectors from similarities across categories. We perform a thorough empirical validation on non-curated tables, a problem seldom studied in machine learning. Results on seven real-world datasets show that similarity encoding brings significant gains in prediction in comparison with known encoding methods for categories or strings, notably one-hot encoding and bag of character n-grams. We draw practical recommendations for encoding dirty categories: 3-gram similarity appears to be a good choice to capture morphological resemblance. For very high-cardinality, dimensionality reduction significantly reduces the computational cost with little loss in performance: random projections or choosing a subset of prototype categories still outperforms classic encoding approaches.

##### Abstract (translated by Google)
对于统计学习，表格中的分类变量通常被视为离散实体，并且被分别编码到特征向量，例如用单热编码。 “非肮脏”的非策划数据会产生具有非常高的基数但具有冗余性的分类变量：几个类别反映相同的实体。在数据库中，这个问题通常通过重复数据删除步骤来解决。我们表明，一个简单的方法，将冗余暴露给学习算法会带来显着的收益。我们研究了一种热门编码的相似性编码的泛化，该编码根据类别间的相似性构建特征向量。我们对非策划表进行了彻底的经验性验证，这是机器学习中很少研究的一个问题。七个真实世界数据集的结果显示，与已知的类别或字符串编码方法相比，相似性编码带来了预测方面的显着增益，值得注意的是单热编码和字符n-gram包。我们为编码脏的类别提出了实用建议：3-gram相似性似乎是捕获形态相似性的好选择。对于非常高的基数，维度降低显着降低了计算成本，而且性能损失很小：随机投影或选择原型类别的子集仍然优于传统编码方法。

##### URL
[http://arxiv.org/abs/1806.00979](http://arxiv.org/abs/1806.00979)

##### PDF
[http://arxiv.org/pdf/1806.00979](http://arxiv.org/pdf/1806.00979)

