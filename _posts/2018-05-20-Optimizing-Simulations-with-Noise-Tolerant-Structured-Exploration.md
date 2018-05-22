---
layout: post
title: "Optimizing Simulations with Noise-Tolerant Structured Exploration"
date: 2018-05-20 22:39:02
categories: arXiv_RO
tags: arXiv_RO Embedding Optimization
author: Krzysztof Choromanski, Atil Iscen, Vikas Sindhwani, Jie Tan, Erwin Coumans
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a simple drop-in noise-tolerant replacement for the standard finite difference procedure used ubiquitously in blackbox optimization. In our approach, parameter perturbation directions are defined by a family of structured orthogonal matrices. We show that at the small cost of computing a Fast Walsh-Hadamard/Fourier Transform (FWHT/FFT), such structured finite differences consistently give higher quality approximation of gradients and Jacobians in comparison to vanilla approaches that use coordinate directions or random Gaussian perturbations. We find that trajectory optimizers like Iterative LQR and Differential Dynamic Programming require fewer iterations to solve several classic continuous control tasks when our methods are used to linearize noisy, blackbox dynamics instead of standard finite differences. By embedding structured exploration in a quasi-Newton optimizer (LBFGS), we are able to learn agile walking and turning policies for quadruped locomotion, that successfully transfer from simulation to actual hardware.We theoretically justify our methods via bounds on the quality of gradient reconstruction and provide a basis for applying them also to nonsmooth problems.

##### Abstract (translated by Google)
我们提出了一个在黑箱优化中无处不在使用的标准有限差分程序的简单插入式噪声容限替换。在我们的方法中，参数摄动方向由结构化正交矩阵族定义。我们表明，在计算快速Walsh-Hadamard /傅立叶变换（FWHT / FFT）的小成本中，与使用坐标方向或随机高斯扰动的香草方法相比，这种结构化有限差分一致地给出梯度和雅可比行为的更高质量近似。当我们的方法被用于线性化噪声，黑箱动力学而不是标准有限差分时，我们发现像迭代LQR和差分动态规划这样的轨迹优化器需要更少的迭代来解决几个经典的连续控制任务。通过在准牛顿优化器（LBFGS）中嵌入结构化探索，我们可以学习四足运动的灵活的步行和转向策略，从而成功地将模拟转化为实际的硬件。我们理论上通过梯度重构的质量边界来验证我们的方法并为将它们应用于非光滑问题提供了基础。

##### URL
[http://arxiv.org/abs/1805.07831](http://arxiv.org/abs/1805.07831)

##### PDF
[http://arxiv.org/pdf/1805.07831](http://arxiv.org/pdf/1805.07831)

