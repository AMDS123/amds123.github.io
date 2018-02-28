---
layout: post
title: "How To Train Your Neural Network Using the Information Bottleneck Principle"
date: 2018-02-27 08:24:19
categories: arXiv_CV
tags: arXiv_CV Optimization Classification
author: Rana Ali Amjad, Bernhard C. Geiger
mathjax: true
---

* content
{:toc}

##### Abstract
In this theory paper, we investigate training deep neural networks (DNNs) for classification via minimizing the information bottleneck (IB) functional. We show that, even if the joint distribution between continuous feature variables and the discrete class variable is known, the resulting optimization problem suffers from two severe issues: First, for deterministic DNNs, the IB functional is infinite for almost all weight matrices, making the optimization problem ill-posed. Second, the invariance of the IB functional under bijections prevents it from capturing desirable properties for classification, such as robustness, architectural simplicity, and simplicity of the learned representation. We argue that these issues are partly resolved for stochastic DNNs, DNNs that include a (hard or soft) decision rule, or by replacing the IB functional with related, but more well-behaved cost functions. We conclude that recent successes reported about training DNNs using the IB framework must be attributed to such solutions. As a side effect, our results imply limitations of the IB framework for the analysis of DNNs.

##### Abstract (translated by Google)
在这篇理论文章中，我们通过最小化信息瓶颈（IB）功能来研究训练深度神经网络（DNN）进行分类。我们证明，即使连续特征变量和离散类变量之间的联合分布是已知的，最终的优化问题也会遇到两个严重问题：首先，对于确定性DNN，几乎所有权矩阵的IB函数都是无限的，优化问题不适当。其次，双射下IB功能的不变性使其无法捕获所需的分类属性，例如鲁棒性，简单的体系结构以及学习表示的简单性。我们认为，对于随机DNN，包括（硬或软）决策规则的DNN，或者通过用相关但性能更好的成本函数替换IB功能，部分解决了这些问题。我们的结论是，最近使用IB框架报告的有关培训DNN的成功必须归功于此类解决方案。作为副作用，我们的结果意味着IBN框架对于DNN分析的局限性。

##### URL
[https://arxiv.org/abs/1802.09766](https://arxiv.org/abs/1802.09766)

##### PDF
[https://arxiv.org/pdf/1802.09766](https://arxiv.org/pdf/1802.09766)

