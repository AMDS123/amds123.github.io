---
layout: post
title: "Causally Regularized Learning with Agnostic Data Selection Bias"
date: 2018-08-19 16:33:36
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning Relation
author: Zheyan Shen, Peng Cui, Kun Kuang, Bo Li, Peixuan Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Most of previous machine learning algorithms are proposed based on the i.i.d. hypothesis. However, this ideal assumption is often violated in real applications, where selection bias may arise between training and testing process. Moreover, in many scenarios, the testing data is not even available during the training process, which makes the traditional methods like transfer learning infeasible due to their need on prior of test distribution. Therefore, how to address the agnostic selection bias for robust model learning is of paramount importance for both academic research and real applications. In this paper, under the assumption that causal relationships among variables are robust across domains, we incorporate causal technique into predictive modeling and propose a novel Causally Regularized Logistic Regression (CRLR) algorithm by jointly optimize global confounder balancing and weighted logistic regression. Global confounder balancing helps to identify causal features, whose causal effect on outcome are stable across domains, then performing logistic regression on those causal features constructs a robust predictive model against the agnostic bias. To validate the effectiveness of our CRLR algorithm, we conduct comprehensive experiments on both synthetic and real world datasets. Experimental results clearly demonstrate that our CRLR algorithm outperforms the state-of-the-art methods, and the interpretability of our method can be fully depicted by the feature visualization.

##### Abstract (translated by Google)
大多数先前的机器学习算法是基于i.i.d提出的。假设。然而，在实际应用中经常违反这种理想假设，其中在训练和测试过程之间可能出现选择偏差。此外，在许多情况下，测试数据在训练过程中甚至不可用，这使得传统学习方法如传统学习因其在测试分发之前的需要而变得不可行。因此，如何针对强大的模型学习来解决不可知的选择偏差对于学术研究和实际应用都是至关重要的。在本文中，假设变量之间的因果关系是跨域的鲁棒性，我们将因果技术结合到预测建模中，并通过联合优化全局混杂平衡和加权逻辑回归提出一种新的因果正则化Logistic回归（CRLR）算法。全局混淆平衡有助于识别因果特征，其结果的因果影响在各个领域是稳定的，然后对这些因果特征进行逻辑回归构建针对不可知缺陷的稳健预测模型。为了验证我们的CRLR算法的有效性，我们对合成和现实世界数据集进行了全面的实验。实验结果清楚地表明，我们的CRLR算法优于最先进的方法，并且我们的方法的可解释性可以通过特征可视化完全描述。

##### URL
[http://arxiv.org/abs/1708.06656](http://arxiv.org/abs/1708.06656)

##### PDF
[http://arxiv.org/pdf/1708.06656](http://arxiv.org/pdf/1708.06656)

