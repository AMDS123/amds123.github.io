---
layout: post
title: "Model-Based Active Source Identification in Complex Environments"
date: 2018-06-20 21:37:36
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Reza Khodayi-mehr, Wilkins Aquino, Michael M. Zavlanos
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we consider the problem of Active Source Identification (ASI) in steady-state Advection-Diffusion (AD) transport systems. Specifically, given a set of noisy concentration measurements, we formulate the Source Identification (SI) problem as a PDE-constrained optimization in function spaces. To obtain a tractable solution, we employ Proper Orthogonal Decomposition to approximate the concentration field by a low dimensional subspace. We also model the unknown source field using nonlinear basis functions, which decreases the number of source parameters drastically. We use the Sensitivity Analysis of the SI objective to initialize the resulting nonlinear optimization problem. To collect the measurements, we control a robot sensor through a sequence of waypoints that maximize the minimum-eigenvalue of the Fisher Information Matrix of the unknown source parameters. Specifically, with every new measurement, the solution of the SI problem is used to determine the next waypoint in a feedback loop. We present numerical simulations and real-world experiments that show that the proposed ASI algorithm can efficiently identify sources in complex AD systems and non-convex domains.

##### Abstract (translated by Google)
在本文中，我们考虑稳态对流扩散（AD）传输系统中的主动源识别（ASI）问题。具体来说，给定一组噪声浓度测量值，我们将源识别（SI）问题制定为函数空间中的PDE约束优化。为了获得易处理的解，我们使用正确的正交分解来通过低维子空间近似浓度场。我们还使用非线性基函数对未知源场进行建模，这大大减少了源参数的数量。我们使用SI目标的灵敏度分析来初始化由此产生的非线性优化问题。为了收集测量数据，我们通过一系列航点控制机器人传感器，以最大化未知源参数的Fisher信息矩阵的最小特征值。具体而言，在每次新的测量中，SI问题的解决方案都用于确定反馈回路中的下一个航点。我们提出的数值模拟和现实世界的实验表明，所提出的ASI算法可以有效地识别复杂AD系统和非凸域中的源。

##### URL
[http://arxiv.org/abs/1706.01603](http://arxiv.org/abs/1706.01603)

##### PDF
[http://arxiv.org/pdf/1706.01603](http://arxiv.org/pdf/1706.01603)

