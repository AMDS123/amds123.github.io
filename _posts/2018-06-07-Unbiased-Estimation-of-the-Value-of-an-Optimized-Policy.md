---
layout: post
title: "Unbiased Estimation of the Value of an Optimized Policy"
date: 2018-06-07 17:12:50
categories: arXiv_AI
tags: arXiv_AI
author: Elon Portugaly, Joseph J. Pfeiffer III
mathjax: true
---

* content
{:toc}

##### Abstract
Randomized trials, also known as A/B tests, are used to select between two policies: a control and a treatment. Given a corresponding set of features, we can ideally learn an optimized policy P that maps the A/B test data features to action space and optimizes reward. However, although A/B testing provides an unbiased estimator for the value of deploying B (i.e., switching from policy A to B), direct application of those samples to learn the the optimized policy P generally does not provide an unbiased estimator of the value of P as the samples were observed when constructing P. In situations where the cost and risks associated of deploying a policy are high, such an unbiased estimator is highly desirable. 
 We present a procedure for learning optimized policies and getting unbiased estimates for the value of deploying them. We wrap any policy learning procedure with a bagging process and obtain out-of-bag policy inclusion decisions for each sample. We then prove that inverse-propensity-weighting effect estimator is unbiased when applied to the optimized subset. Likewise, we apply the same idea to obtain out-of-bag unbiased per-sample value estimate of the measurement that is independent of the randomized treatment, and use these estimates to build an unbiased doubly-robust effect estimator. Lastly, we empirically shown that even when the average treatment effect is negative we can find a positive optimized policy.

##### Abstract (translated by Google)
随机试验也称为A / B试验，用于在两种策略之间进行选择：对照和治疗。给定一组相应的功能，我们可以理想地学习一个优化策略P，将A / B测试数据特征映射到行动空间并优化奖励。然而，尽管A / B测试为部署B的价值提供了一个无偏估计（即从策略A切换到B），但直接应用这些样本来学习优化策略P通常不会提供该值的无偏估计量的P，因为在构建P时观察样本。在部署策略相关的成本和风险较高的情况下，非常需要这样的无偏​​估计。
 我们提出了一个学习优化策略的程序，并获得了部署它们的价值的无偏估计。我们用套袋过程包装任何策略学习过程，并为每个样本获取袋外策略包含决策。然后我们证明当应用于优化子集时，反倾向加权效应估计器是无偏的。同样，我们应用相同的想法来获得独立于随机治疗的测量值的无偏差的每样本值估计值，并使用这些估计值来构建无偏的双稳健效应估计值。最后，我们凭经验证明，即使平均治疗效果为负值，我们也可以找到一个积极的优化政策。

##### URL
[http://arxiv.org/abs/1806.02794](http://arxiv.org/abs/1806.02794)

##### PDF
[http://arxiv.org/pdf/1806.02794](http://arxiv.org/pdf/1806.02794)

