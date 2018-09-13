---
layout: post
title: "Optimization with Non-Differentiable Constraints with Applications to Fairness, Recall, Churn, and Other Goals"
date: 2018-09-11 23:41:47
categories: arXiv_AI
tags: arXiv_AI Optimization Prediction
author: Andrew Cotter, Heinrich Jiang, Serena Wang, Taman Narayan, Maya Gupta, Seungil You, Karthik Sridharan
mathjax: true
---

* content
{:toc}

##### Abstract
We show that many machine learning goals, such as improved fairness metrics, can be expressed as constraints on the model's predictions, which we call rate constraints. We study the problem of training non-convex models subject to these rate constraints (or any non-convex and non-differentiable constraints). In the non-convex setting, the standard approach of Lagrange multipliers may fail. Furthermore, if the constraints are non-differentiable, then one cannot optimize the Lagrangian with gradient-based methods. To solve these issues, we introduce the proxy-Lagrangian formulation. This new formulation leads to an algorithm that produces a stochastic classifier by playing a two-player non-zero-sum game solving for what we call a semi-coarse correlated equilibrium, which in turn corresponds to an approximately optimal and feasible solution to the constrained optimization problem. We then give a procedure which shrinks the randomized solution down to one that is a mixture of at most $m+1$ deterministic solutions, given $m$ constraints. This culminates in algorithms that can solve non-convex constrained optimization problems with possibly non-differentiable and non-convex constraints with theoretical guarantees. We provide extensive experimental results enforcing a wide range of policy goals including different fairness metrics, and other goals on accuracy, coverage, recall, and churn.

##### Abstract (translated by Google)
我们表明，许多机器学习目标，例如改进的公平度量，可以表示为模型预测的约束，我们称之为速率约束。我们研究了受这些速率约束（或任何非凸和非可微约束）训练的非凸模型的问题。在非凸设置中，拉格朗日乘数的标准方法可能失败。此外，如果约束是不可微分的，则不能用基于梯度的方法优化拉格朗日。为了解决这些问题，我们引入了代理拉格朗日公式。这个新的公式导致了一种算法，通过玩一个双人非零和游戏来解决我们称之为半粗相关的均衡，从而产生一个随机分类器，这又对应于约束的近似最优和可行的解决方案。优化问题。然后我们给出一个程序，将随机化解决方案缩减到最多$ m + 1 $确定性解决方案的混合，给定$ m $约束。这最终导致算法可以解决非凸约束优化问题，可能具有理论保证的非可微分和非凸约束。我们提供广泛的实验结果，执行广泛的政策目标，包括不同的公平指标，以及准确性，覆盖范围，召回和客户流失的其他目标。

##### URL
[http://arxiv.org/abs/1809.04198](http://arxiv.org/abs/1809.04198)

##### PDF
[http://arxiv.org/pdf/1809.04198](http://arxiv.org/pdf/1809.04198)

