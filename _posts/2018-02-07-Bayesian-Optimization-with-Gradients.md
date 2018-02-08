---
layout: post
title: "Bayesian Optimization with Gradients"
date: 2018-02-07 04:05:29
categories: arXiv_AI
tags: arXiv_AI Knowledge Optimization Inference Deep_Learning
author: Jian Wu, Matthias Poloczek, Andrew Gordon Wilson, Peter I. Frazier
mathjax: true
---

* content
{:toc}

##### Abstract
Bayesian optimization has been successful at global optimization of expensive-to-evaluate multimodal objective functions. However, unlike most optimization methods, Bayesian optimization typically does not use derivative information. In this paper we show how Bayesian optimization can exploit derivative information to decrease the number of objective function evaluations required for good performance. In particular, we develop a novel Bayesian optimization algorithm, the derivative-enabled knowledge-gradient (dKG), for which we show one-step Bayes-optimality, asymptotic consistency, and greater one-step value of information than is possible in the derivative-free setting. Our procedure accommodates noisy and incomplete derivative information, comes in both sequential and batch forms, and can optionally reduce the computational cost of inference through automatically selected retention of a single directional derivative. We also compute the d-KG acquisition function and its gradient using a novel fast discretization-free technique. We show d-KG provides state-of-the-art performance compared to a wide range of optimization procedures with and without gradients, on benchmarks including logistic regression, deep learning, kernel learning, and k-nearest neighbors.

##### Abstract (translated by Google)
贝叶斯优化在昂贵的评估多目标函数的全局优化方面取得了成功。但是，与大多数优化方法不同，贝叶斯优化通常不使用派生信息。在本文中，我们展示了贝叶斯优化如何利用导数信息来减少为获得良好性能所需的目标函数评估的数量。具体而言，我们开发了一种新颖的贝叶斯优化算法，即导数启用知识梯度（dKG），对于这种算法，我们显示了一步贝叶斯最优性，渐近一致性以及信息的更大的一步值免费设置。我们的程序适应嘈杂和不完整的派生信息，有连续和批量形式，并可以选择性地通过自动选择保留单向导数来降低推理的计算成本。我们还使用一种新型的快速无离散化技术来计算d-KG采集函数及其梯度。我们展示了d-KG提供最先进的性能，与包括logistic回归，深度学习，核心学习和k最近邻的基准在内的广泛的优化程序相比，有梯度和无梯度。

##### URL
[http://arxiv.org/abs/1703.04389](http://arxiv.org/abs/1703.04389)

##### PDF
[http://arxiv.org/pdf/1703.04389](http://arxiv.org/pdf/1703.04389)

