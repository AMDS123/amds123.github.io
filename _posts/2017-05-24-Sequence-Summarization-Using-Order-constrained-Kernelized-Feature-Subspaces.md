---
layout: post
title: "Sequence Summarization Using Order-constrained Kernelized Feature Subspaces"
date: 2017-05-24 02:11:04
categories: arXiv_CV
tags: arXiv_CV Summarization Action_Recognition Optimization Recognition
author: Anoop Cherian, Suvrit Sra, Richard Hartley
mathjax: true
---

* content
{:toc}

##### Abstract
Representations that can compactly and effectively capture temporal evolution of semantic content are important to machine learning algorithms that operate on multi-variate time-series data. We investigate such representations motivated by the task of human action recognition. Here each data instance is encoded by a multivariate feature (such as via a deep CNN) where action dynamics are characterized by their variations in time. As these features are often non-linear, we propose a novel pooling method, kernelized rank pooling, that represents a given sequence compactly as the pre-image of the parameters of a hyperplane in an RKHS, projections of data onto which captures their temporal order. We develop this idea further and show that such a pooling scheme can be cast as an order-constrained kernelized PCA objective; we then propose to use the parameters of a kernelized low-rank feature subspace as the representation of the sequences. We cast our formulation as an optimization problem on generalized Grassmann manifolds and then solve it efficiently using Riemannian optimization techniques. We present experiments on several action recognition datasets using diverse feature modalities and demonstrate state-of-the-art results.

##### Abstract (translated by Google)
能够紧凑而有效地捕捉语义内容的时间演进的表示对于在多变量时间序列数据上操作的机器学习算法是重要的。我们调查这种表现是由人类行为识别的任务驱动的。在这里，每个数据实例都由一个多变量特征（例如通过深度CNN）进行编码，其中动作动态以时间变化为特征。由于这些特征往往是非线性的，我们提出了一种新颖的池化方法，核化的级联池，它将一个给定的序列紧凑地表示为RKHS中超平面参数的预映像，在其上捕获它们的时间顺序的数据的投影。我们进一步发展这个想法，并表明这样一个池化方案可以作为一个有序约束核化的PCA目标;然后我们提出使用核化的低秩特征子空间的参数作为序列的表示。我们把我们的公式作为广义Grassmann流形上的优化问题，然后用黎曼优化技术有效地解决它。我们提出了使用不同特征模式的几个动作识别数据集的实验，并展示了最先进的结果。

##### URL
[https://arxiv.org/abs/1705.08583](https://arxiv.org/abs/1705.08583)

##### PDF
[https://arxiv.org/pdf/1705.08583](https://arxiv.org/pdf/1705.08583)

