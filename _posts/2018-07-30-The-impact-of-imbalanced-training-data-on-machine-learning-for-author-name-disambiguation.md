---
layout: post
title: "The impact of imbalanced training data on machine learning for author name disambiguation"
date: 2018-07-30 14:29:27
categories: arXiv_CL
tags: arXiv_CL Attention
author: Jinseok Kim, Jenna Kim
mathjax: true
---

* content
{:toc}

##### Abstract
In supervised machine learning for author name disambiguation, negative training data are often dominantly larger than positive training data. This paper examines how the ratios of negative to positive training data can affect the performance of machine learning algorithms to disambiguate author names in bibliographic records. On multiple labeled datasets, three classifiers - Logistic Regression, Na\"ive Bayes, and Random Forest - are trained through representative features such as coauthor names, and title words extracted from the same training data but with various positive-negative training data ratios. Results show that increasing negative training data can improve disambiguation performance but with a few percent of performance gains and sometimes degrade it. Logistic and Na\"ive Bayes learn optimal disambiguation models even with a base ratio (1:1) of positive and negative training data. Also, the performance improvement by Random Forest tends to quickly saturate roughly after 1:10 ~ 1:15. These findings imply that contrary to the common practice using all training data, name disambiguation algorithms can be trained using part of negative training data without degrading much disambiguation performance while increasing computational efficiency. This study calls for more attention from author name disambiguation scholars to methods for machine learning from imbalanced data.

##### Abstract (translated by Google)
在用于作者名称消歧的监督机器学习中，负训练数据通常主要大于正训练数据。本文探讨了负面训练数据与正面训练数据的比率如何影响机器学习算法的性能，以消除书目记录中作者姓名的歧义。在多个标记数据集上，通过代表性特征（例如共同作者名称）和从相同训练数据中提取但具有各种正 - 负训练数据比率的标题词来训练三个分类器 - 逻辑回归，Na \“ive Bayes和随机森林 - 。结果表明，增加负面训练数据可以提高消歧性能，但只有几个百分点的性能提升，有时会降低它。即使是正面和负面训练的基本比例（1：1），Logistic和Na \'Bayes也会学习最佳的消歧模型数据。此外，随机森林的性能提升往往会在1:10~1：15之后迅速饱和。这些发现意味着与使用所有训练数据的常规做法相反，可以使用部分负训练数据训练名称消歧算法，而不会降低很多消歧性能，同时提高计算效率。这项研究需要更多的注意力从作者名称消歧学者到不平衡数据的机器学习方法。

##### URL
[http://arxiv.org/abs/1808.00525](http://arxiv.org/abs/1808.00525)

##### PDF
[http://arxiv.org/pdf/1808.00525](http://arxiv.org/pdf/1808.00525)

