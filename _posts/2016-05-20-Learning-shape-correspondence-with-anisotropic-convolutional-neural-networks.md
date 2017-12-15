---
layout: post
title: "Learning shape correspondence with anisotropic convolutional neural networks"
date: 2016-05-20 17:02:40
categories: arXiv_CV
tags: arXiv_CV CNN
author: Davide Boscaini, Jonathan Masci, Emanuele Rodolà, Michael M. Bronstein
mathjax: true
---

* content
{:toc}

##### Abstract
Establishing correspondence between shapes is a fundamental problem in geometry processing, arising in a wide variety of applications. The problem is especially difficult in the setting of non-isometric deformations, as well as in the presence of topological noise and missing parts, mainly due to the limited capability to model such deformations axiomatically. Several recent works showed that invariance to complex shape transformations can be learned from examples. In this paper, we introduce an intrinsic convolutional neural network architecture based on anisotropic diffusion kernels, which we term Anisotropic Convolutional Neural Network (ACNN). In our construction, we generalize convolutions to non-Euclidean domains by constructing a set of oriented anisotropic diffusion kernels, creating in this way a local intrinsic polar representation of the data (`patch'), which is then correlated with a filter. Several cascades of such filters, linear, and non-linear operators are stacked to form a deep neural network whose parameters are learned by minimizing a task-specific cost. We use ACNNs to effectively learn intrinsic dense correspondences between deformable shapes in very challenging settings, achieving state-of-the-art results on some of the most difficult recent correspondence benchmarks.

##### Abstract (translated by Google)
建立形状之间的对应关系是几何处理中的一个基本问题，在各种各样的应用中产生。在非等距变形的设置以及存在拓扑噪声和缺失部分的情况下，这个问题特别困难，主要是由于公理模拟这种变形的能力有限。最近的几个作品表明，可以从例子中学习到对于复杂形状变换的不变性。本文介绍了一种基于各向异性扩散核的内在卷积神经网络结构，我们称之为各向异性卷积神经网络（ACNN）。在我们的构造中，我们通过构造一组取向各向异性扩散内核来将卷积推广到非欧几里德域，从而以这种方式创建数据的局部极性表示（“贴片”），然后将其与滤波器相关联。几个这样的滤波器级联，线性和非线性算子堆叠形成深度神经网络，其参数通过最小化任务特定的成本来学习。我们使用ACNN在非常具有挑战性的环境中有效地学习可变形形状之间的内在密集对应关系，在最近一些最困难的通信基准测试中获得了最新的结果。

##### URL
[https://arxiv.org/abs/1605.06437](https://arxiv.org/abs/1605.06437)

##### PDF
[https://arxiv.org/pdf/1605.06437](https://arxiv.org/pdf/1605.06437)

