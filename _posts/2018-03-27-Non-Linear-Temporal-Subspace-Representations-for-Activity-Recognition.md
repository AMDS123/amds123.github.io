---
layout: post
title: "Non-Linear Temporal Subspace Representations for Activity Recognition"
date: 2018-03-27 20:11:04
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Optimization Recognition
author: Anoop Cherian, Suvrit Sra, Stephen Gould, Richard Hartley
mathjax: true
---

* content
{:toc}

##### Abstract
Representations that can compactly and effectively capture the temporal evolution of semantic content are important to computer vision and machine learning algorithms that operate on multi-variate time-series data. We investigate such representations motivated by the task of human action recognition. Here each data instance is encoded by a multivariate feature (such as via a deep CNN) where action dynamics are characterized by their variations in time. As these features are often non-linear, we propose a novel pooling method, kernelized rank pooling, that represents a given sequence compactly as the pre-image of the parameters of a hyperplane in a reproducing kernel Hilbert space, projections of data onto which captures their temporal order. We develop this idea further and show that such a pooling scheme can be cast as an order-constrained kernelized PCA objective. We then propose to use the parameters of a kernelized low-rank feature subspace as the representation of the sequences. We cast our formulation as an optimization problem on generalized Grassmann manifolds and then solve it efficiently using Riemannian optimization techniques. We present experiments on several action recognition datasets using diverse feature modalities and demonstrate state-of-the-art results.

##### Abstract (translated by Google)
能够紧凑而有效地捕捉语义内容的时间演变的表示对于运行在多变量时间序列数据上的计算机视觉和机器学习算法是重要的。我们调查这种由人类行为识别任务驱动的表征。在这里，每个数据实例都由多变量特征（例如通过深度CNN）进行编码，其中动作动态以其时间变化为特征。由于这些特征通常是非线性的，我们提出了一种新颖的池化方法，核化级联池，它将一个给定的序列紧凑地表示为再生核Hilbert空间中超平面参数的预映像，捕获的数据投影他们的时间顺序。我们进一步发展这个想法，并表明这样一个池化方案可以作为一个有序约束核化的PCA目标。然后我们提出使用核化的低秩特征子空间的参数作为序列的表示。我们将我们的公式作为广义Grassmann流形上的优化问题，然后使用黎曼优化技术有效地解决它。我们使用不同的特征模式在多个动作识别数据集上展示实验，并展示最先进的结果。

##### URL
[http://arxiv.org/abs/1803.11064](http://arxiv.org/abs/1803.11064)

##### PDF
[http://arxiv.org/pdf/1803.11064](http://arxiv.org/pdf/1803.11064)

