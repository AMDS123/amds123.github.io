---
layout: post
title: "Boolean Decision Rules via Column Generation"
date: 2018-05-24 21:12:26
categories: arXiv_AI
tags: arXiv_AI Classification
author: Sanjeeb Dash, Oktay G&#xfc;nl&#xfc;k, Dennis Wei
mathjax: true
---

* content
{:toc}

##### Abstract
This paper considers the learning of Boolean rules in either disjunctive normal form (DNF, OR-of-ANDs, equivalent to decision rule sets) or conjunctive normal form (CNF, AND-of-ORs) as an interpretable model for classification. An integer program is formulated to optimally trade classification accuracy for rule simplicity. Column generation (CG) is used to efficiently search over an exponential number of candidate clauses (conjunctions or disjunctions) without the need for heuristic rule mining. This approach also bounds the gap between the selected rule set and the best possible rule set on the training data. To handle large datasets, we propose an approximate CG algorithm using randomization. Compared to three recently proposed alternatives, the CG algorithm dominates the accuracy-simplicity trade-off in 7 out of 15 datasets. When maximized for accuracy, CG is competitive with rule learners designed for this purpose, sometimes finding significantly simpler solutions that are no less accurate.

##### Abstract (translated by Google)
本文考虑布尔规则的学习，以分离正态形式（DNF，OR-AND-ANDs，等同于决策规则集合）或联合正规形式（CNF，AND-OR）作为可解释的分类模型。一个整数程序的制定是为了优化规则交易的分类准确性。列生成（CG）用于在不需要启发式规则挖掘的情况下高效搜索指数数量的候选子句（连词或分离）。这种方法也限制了所选择的规则集和训练数据上的最佳可能规则集之间的差距。为了处理大型数据集，我们提出了一种使用随机化的近似CG算法。与最近提出的三种替代方案相比，CG算法在15个数据集中的7个数据集中支配精度 - 简单性之间的平衡。当准确性最大化时，CG与为此目的而设计的规则学习者相比具有竞争力，有时会发现更简单的解决方案，这些解决方案同样精确。

##### URL
[http://arxiv.org/abs/1805.09901](http://arxiv.org/abs/1805.09901)

##### PDF
[http://arxiv.org/pdf/1805.09901](http://arxiv.org/pdf/1805.09901)

