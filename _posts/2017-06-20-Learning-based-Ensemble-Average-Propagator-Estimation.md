---
layout: post
title: "Learning-based Ensemble Average Propagator Estimation"
date: 2017-06-20 03:55:50
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Chuyang Ye
mathjax: true
---

* content
{:toc}

##### Abstract
By capturing the anisotropic water diffusion in tissue, diffusion magnetic resonance imaging (dMRI) provides a unique tool for noninvasively probing the tissue microstructure and orientation in the human brain. The diffusion profile can be described by the ensemble average propagator (EAP), which is inferred from observed diffusion signals. However, accurate EAP estimation using the number of diffusion gradients that is clinically practical can be challenging. In this work, we propose a deep learning algorithm for EAP estimation, which is named learning-based ensemble average propagator estimation (LEAPE). The EAP is commonly represented by a basis and its associated coefficients, and here we choose the SHORE basis and design a deep network to estimate the coefficients. The network comprises two cascaded components. The first component is a multiple layer perceptron (MLP) that simultaneously predicts the unknown coefficients. However, typical training loss functions, such as mean squared errors, may not properly represent the geometry of the possibly non-Euclidean space of the coefficients, which in particular causes problems for the extraction of directional information from the EAP. Therefore, to regularize the training, in the second component we compute an auxiliary output of approximated fiber orientation (FO) errors with the aid of a second MLP that is trained separately. We performed experiments using dMRI data that resemble clinically achievable $q$-space sampling, and observed promising results compared with the conventional EAP estimation method.

##### Abstract (translated by Google)
通过捕获组织中的各向异性水扩散，扩散磁共振成像（dMRI）提供了一种独特的工具，可以非侵入性地探测人脑中的组织微观结构和取向。扩散剖面可以由集合平均传播子（EAP）来描述，这是从观测到的扩散信号推断出来的。然而，使用临床实用的扩散梯度的数量进行准确的EAP评估可能是具有挑战性的。在这项工作中，我们提出了一个EAP估计的深度学习算法，它被称为基于学习的集合平均传播者估计（LEAPE）。 EAP通常由一个基础及其相关系数表示，这里我们选择SHORE基础，并设计一个深度网络来估计系数。该网络包含两个级联组件。第一个组件是一个多层感知器（MLP），它同时预测未知系数。然而，典型的训练损失函数，例如均方误差，可能无法正确表示系数的可能非欧几里得空间的几何形状，这尤其导致从EAP提取方向信息的问题。因此，为了正规化训练，在第二部分中，我们借助于分开训练的第二MLP来计算近似纤维取向（FO）误差的辅助输出。我们使用dMRI数据进行实验，这些数据类似于临床上可实现的$ q $  - 空间采样，并且与传统的EAP估计方法相比，观察到有希望的结果。

##### URL
[https://arxiv.org/abs/1706.06258](https://arxiv.org/abs/1706.06258)

##### PDF
[https://arxiv.org/pdf/1706.06258](https://arxiv.org/pdf/1706.06258)

