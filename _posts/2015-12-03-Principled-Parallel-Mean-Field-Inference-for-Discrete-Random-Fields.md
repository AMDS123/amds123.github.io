---
layout: post
title: "Principled Parallel Mean-Field Inference for Discrete Random Fields"
date: 2015-12-03 10:26:03
categories: arXiv_CV
tags: arXiv_CV Optimization Inference
author: Pierre Baqué, Timur Bagautdinov, François Fleuret, Pascal Fua
mathjax: true
---

* content
{:toc}

##### Abstract
Mean-field variational inference is one of the most popular approaches to inference in discrete random fields. Standard mean-field optimization is based on coordinate descent and in many situations can be impractical. Thus, in practice, various parallel techniques are used, which either rely on ad-hoc smoothing with heuristically set parameters, or put strong constraints on the type of models. In this paper, we propose a novel proximal gradient-based approach to optimizing the variational objective. It is naturally parallelizable and easy to implement. We prove its convergence, and then demonstrate that, in practice, it yields faster convergence and often finds better optima than more traditional mean-field optimization techniques. Moreover, our method is less sensitive to the choice of parameters.

##### Abstract (translated by Google)
平均场变分推断是离散随机场中最流行的推理方法之一。标准的平均场优化是基于坐标下降的，在许多情况下是不切实际的。因此，在实践中，使用各种并行技术，或者依赖于启发式设置参数的特设平滑，或者对模型类型施加强约束。在本文中，我们提出了一种新的基于近端梯度的方法来优化变分目标。这是自然而然的并且易于实现。我们证明了它的收敛性，然后证明在实践中，它比较传统的平均场优化技术产生更快的收敛速度并且经常发现更好的最优化。而且，我们的方法对参数的选择较不敏感。

##### URL
[https://arxiv.org/abs/1511.06103](https://arxiv.org/abs/1511.06103)

##### PDF
[https://arxiv.org/pdf/1511.06103](https://arxiv.org/pdf/1511.06103)

