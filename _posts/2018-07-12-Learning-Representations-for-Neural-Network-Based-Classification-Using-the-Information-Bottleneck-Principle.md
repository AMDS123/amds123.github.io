---
layout: post
title: "Learning Representations for Neural Network-Based Classification Using the Information Bottleneck Principle"
date: 2018-07-12 06:40:42
categories: arXiv_CV
tags: arXiv_CV Optimization Classification
author: Rana Ali Amjad, Bernhard C. Geiger
mathjax: true
---

* content
{:toc}

##### Abstract
In this theory paper, we investigate training deep neural networks (DNNs) for classification via minimizing the information bottleneck (IB) functional. We show that the resulting optimization problem suffers from two severe issues: First, for deterministic DNNs, either the IB functional is infinite for almost all values of network parameters, making the optimization problem ill-posed, or it is piecewise constant, hence not admitting gradient-based optimization methods. Second, the invariance of the IB functional under bijections prevents it from capturing desirable properties for classification, such as robustness, architectural simplicity, and simplicity of the learned representation. We argue that these issues are partly resolved for stochastic DNNs, DNNs that include a (hard or soft) decision rule, or by replacing the IB functional with related, but more well-behaved cost functions. We conclude that recent successes reported about training DNNs using the IB framework must be attributed to such solutions. As a side effect, our results imply limitations of the IB framework for the analysis of DNNs. We also note that rather than trying to repair the inherent problems in IB functional, a better approach may be to design regularizers on latent representation enforcing the desired properties directly.

##### Abstract (translated by Google)
在这篇理论论文中，我们通过最小化信息瓶颈（IB）功能来研究训练深度神经网络（DNN）的分类。我们表明，由此产生的优化问题存在两个严重问题：首先，对于确定性DNN，IB功能对于几乎所有网络参数值都是无限的，使得优化问题不适合，或者它是分段常数，因此不承认基于梯度的优化方法。其次，IB在双射下的功能的不变性使其无法捕获用于分类的期望属性，例如鲁棒性，架构简单性和学习表示的简单性。我们认为，对于随机DNN，包含（硬或软）决策规则的DNN，或者通过将IB功能替换为相关但更加良好的成本函数，这些问题部分得到解决。我们得出结论，最近关于使用IB框架培训DNN的成功报告必须归功于此类解决方案。作为副作用，我们的结果意味着IB框架对DNN分析的局限性。我们还注意到，不是试图修复IB功能中的固有问题，更好的方法可能是设计关于潜在表示的正则化器，直接强制执行所需的属性。

##### URL
[http://arxiv.org/abs/1802.09766](http://arxiv.org/abs/1802.09766)

##### PDF
[http://arxiv.org/pdf/1802.09766](http://arxiv.org/pdf/1802.09766)

