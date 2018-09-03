---
layout: post
title: "Boosting Binary Optimization via Binary Classification: A Case Study of Job Shop Scheduling"
date: 2018-08-31 15:42:55
categories: arXiv_AI
tags: arXiv_AI Optimization Classification Prediction
author: Oleg V. Shylo, Hesam Shams
mathjax: true
---

* content
{:toc}

##### Abstract
Many optimization techniques evaluate solutions consecutively, where the next candidate for evaluation is determined by the results of previous evaluations. For example, these include iterative methods, "black box" optimization algorithms, simulated annealing, evolutionary algorithms and tabu search, to name a few. When solving an optimization problem, these algorithms evaluate a large number of solutions, which raises the following question: Is it possible to learn something about the optimum using these solutions? In this paper, we define this "learning" question in terms of a logistic regression model and explore its predictive accuracy computationally. The proposed model uses a collection of solutions to predict the components of the optimal solutions. To illustrate the utility of such predictions, we embed the logistic regression model into the tabu search algorithm for job shop scheduling problem. The resulting framework is simple to implement, yet provides a significant boost to the performance of the standard tabu search.

##### Abstract (translated by Google)
许多优化技术连续地评估解决方案，其中下一个评估候选者由先前评估的结果确定。例如，这些包括迭代方法，“黑盒子”优化算法，模拟退火，进化算法和禁忌搜索，仅举几例。在解决优化问题时，这些算法会评估大量解决方案，从而引发了以下问题：是否可以使用这些解决方案了解最佳解决方案？在本文中，我们根据逻辑回归模型定义这个“学习”问题，并在计算上探索其预测精度。所提出的模型使用一组解决方案来预测最优解的组成部分。为了说明这种预测的效用，我们将逻辑回归模型嵌入到禁忌搜索算法中，用于车间调度问题。生成的框架易于实现，但却显着提高了标准禁忌搜索的性能。

##### URL
[http://arxiv.org/abs/1808.10813](http://arxiv.org/abs/1808.10813)

##### PDF
[http://arxiv.org/pdf/1808.10813](http://arxiv.org/pdf/1808.10813)

