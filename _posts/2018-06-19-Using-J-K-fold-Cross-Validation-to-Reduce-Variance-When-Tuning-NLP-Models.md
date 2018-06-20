---
layout: post
title: "Using J-K fold Cross Validation to Reduce Variance When Tuning NLP Models"
date: 2018-06-19 10:12:25
categories: arXiv_CL
tags: arXiv_CL Sentiment Sentiment_Classification Classification Recommendation
author: Henry B.Moss, David S.Leslie, Paul Rayson
mathjax: true
---

* content
{:toc}

##### Abstract
K-fold cross validation (CV) is a popular method for estimating the true performance of machine learning models, allowing model selection and parameter tuning. However, the very process of CV requires random partitioning of the data and so our performance estimates are in fact stochastic, with variability that can be substantial for natural language processing tasks. We demonstrate that these unstable estimates cannot be relied upon for effective parameter tuning. The resulting tuned parameters are highly sensitive to how our data is partitioned, meaning that we often select sub-optimal parameter choices and have serious reproducibility issues. 
 Instead, we propose to use the less variable J-K-fold CV, in which J independent K-fold cross validations are used to assess performance. Our main contributions are extending J-K-fold CV from performance estimation to parameter tuning and investigating how to choose J and K. We argue that variability is more important than bias for effective tuning and so advocate lower choices of K than are typically seen in the NLP literature, instead use the saved computation to increase J. To demonstrate the generality of our recommendations we investigate a wide range of case-studies: sentiment classification (both general and target-specific), part-of-speech tagging and document classification.

##### Abstract (translated by Google)
K-fold交叉验证（CV）是评估机器学习模型真实性能的常用方法，可用于模型选择和参数调整。然而，CV的过程需要对数据进行随机分割，因此我们的性能估计实际上是随机的，对于自然语言处理任务而言，可变性可能很大。我们证明这些不稳定的估计值不能用于有效的参数调整。由此产生的调谐参数对我们的数据如何分区非常敏感，这意味着我们经常选择次优参数选择并且存在严重的重复性问题。
 相反，我们建议使用较少变量的J-K-fold CV，其中使用J个独立的K-fold交叉验证来评估性能。我们的主要贡献是将JK-fold CV从性能估计扩展到参数调整并研究如何选择J和K.我们认为变异性比有偏调的偏好更重要，因此主张K的选择比NLP中典型的选择要少文献，而是使用保存的计算来增加J.为了证明我们推荐的一般性，我们调查了大量的案例研究：情感分类（普通和特定目标），词性标注和文档分类。

##### URL
[http://arxiv.org/abs/1806.07139](http://arxiv.org/abs/1806.07139)

##### PDF
[http://arxiv.org/pdf/1806.07139](http://arxiv.org/pdf/1806.07139)

