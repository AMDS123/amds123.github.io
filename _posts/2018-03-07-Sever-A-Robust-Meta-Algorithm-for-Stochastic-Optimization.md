---
layout: post
title: "Sever: A Robust Meta-Algorithm for Stochastic Optimization"
date: 2018-03-07 18:47:48
categories: arXiv_AI
tags: arXiv_AI Optimization Classification Gradient_Descent
author: Ilias Diakonikolas, Gautam Kamath, Daniel M. Kane, Jerry Li, Jacob Steinhardt, Alistair Stewart
mathjax: true
---

* content
{:toc}

##### Abstract
In high dimensions, most machine learning methods are brittle to even a small fraction of structured outliers. To address this, we introduce a new meta-algorithm that can take in a base learner such as least squares or stochastic gradient descent, and harden the learner to be resistant to outliers. Our method, Sever, possesses strong theoretical guarantees yet is also highly scalable -- beyond running the base learner itself, it only requires computing the top singular vector of a certain $n \times d$ matrix. We apply Sever on a drug design dataset and a spam classification dataset, and find that in both cases it has substantially greater robustness than several baselines. On the spam dataset, with $1\%$ corruptions, we achieved $7.4\%$ test error, compared to $13.4\%-20.5\%$ for the baselines, and $3\%$ error on the uncorrupted dataset. Similarly, on the drug design dataset, with $10\%$ corruptions, we achieved $1.42$ mean-squared error test error, compared to $1.51$-$2.33$ for the baselines, and $1.23$ error on the uncorrupted dataset.

##### Abstract (translated by Google)
在高维方面，大多数机器学习方法都很脆弱，即使是一小部分结构化的异常值也是如此。为了解决这个问题，我们引入了一种新的元算法，可以接受基础学习者，如最小二乘或随机梯度下降，并强化学习者抵抗异常值。我们的方法Sever具有强大的理论保证，但也具有高度的可扩展性 - 除了运行基本学习器本身外，它只需要计算某个$ n \ times d $矩阵的顶部奇异向量。我们将Sever应用于药物设计数据集和垃圾邮件分类数据集，并发现在两种情况下，它都比几个基线具有更强的稳健性。在垃圾邮件数据集上，出现$ 1 \％$损坏，我们实现了$ 7.4 \％$ test错误，而基线为$ 13.4 \％ -  20.5 \％$，未损坏数据集为$ 3 \％$错误。同样，在药物设计数据集中，出现$ 10 \％$损坏，我们实现了1.42美元的均方根误差测试误差，而基线为1.51美元 -  2.33美元，未损坏数据集为1.23美元。

##### URL
[http://arxiv.org/abs/1803.02815](http://arxiv.org/abs/1803.02815)

##### PDF
[http://arxiv.org/pdf/1803.02815](http://arxiv.org/pdf/1803.02815)

