---
layout: post
title: "Stochastic Variational Inference with Gradient Linearization"
date: 2018-03-28 13:22:57
categories: arXiv_CV
tags: arXiv_CV Face Optimization Inference
author: Tobias Plötz, Anne S. Wannenwetsch, Stefan Roth
mathjax: true
---

* content
{:toc}

##### Abstract
Variational inference has experienced a recent surge in popularity owing to stochastic approaches, which have yielded practical tools for a wide range of model classes. A key benefit is that stochastic variational inference obviates the tedious process of deriving analytical expressions for closed-form variable updates. Instead, one simply needs to derive the gradient of the log-posterior, which is often much easier. Yet for certain model classes, the log-posterior itself is difficult to optimize using standard gradient techniques. One such example are random field models, where optimization based on gradient linearization has proven popular, since it speeds up convergence significantly and can avoid poor local optima. In this paper we propose stochastic variational inference with gradient linearization (SVIGL). It is similarly convenient as standard stochastic variational inference - all that is required is a local linearization of the energy gradient. Its benefit over stochastic variational inference with conventional gradient methods is a clear improvement in convergence speed, while yielding comparable or even better variational approximations in terms of KL divergence. We demonstrate the benefits of SVIGL in three applications: Optical flow estimation, Poisson-Gaussian denoising, and 3D surface reconstruction.

##### Abstract (translated by Google)
随机方法使变分推理经历了最近的普及，这些随机方法已经为广泛的模型类产生了实用的工具。一个关键的好处是随机变分推理避免了导出闭式变量更新的解析表达式的繁琐过程。相反，人们只需要推导出log-posterior的梯度，这往往更容易。然而对于某些模型类，使用标准梯度技术难以优化对数后验本身。一个这样的例子是随机场模型，其中基于梯度线性化的优化已经被证明是流行的，因为它显着地加快了收敛并且可以避免差的局部最优。本文提出了带有梯度线性化的随机变分推理（SVIGL）。它与标准随机变分推理同样方便 - 所需要的只是能量梯度的局部线性化。它对传统梯度方法随机变分推理的好处是收敛速度明显改善，同时在KL散度方面产生可比或甚至更好的变分近似。我们在三个应用中展示了SVIGL的优势：光流估计，泊松高斯去噪和三维曲面重建。

##### URL
[https://arxiv.org/abs/1803.10586](https://arxiv.org/abs/1803.10586)

##### PDF
[https://arxiv.org/pdf/1803.10586](https://arxiv.org/pdf/1803.10586)

