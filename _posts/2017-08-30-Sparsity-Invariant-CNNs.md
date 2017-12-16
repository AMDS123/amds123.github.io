---
layout: post
title: "Sparsity Invariant CNNs"
date: 2017-08-30 18:12:47
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Prediction
author: Jonas Uhrig, Nick Schneider, Lukas Schneider, Uwe Franke, Thomas Brox, Andreas Geiger
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we consider convolutional neural networks operating on sparse inputs with an application to depth upsampling from sparse laser scan data. First, we show that traditional convolutional networks perform poorly when applied to sparse data even when the location of missing data is provided to the network. To overcome this problem, we propose a simple yet effective sparse convolution layer which explicitly considers the location of missing data during the convolution operation. We demonstrate the benefits of the proposed network architecture in synthetic and real experiments with respect to various baseline approaches. Compared to dense baselines, the proposed sparse convolution network generalizes well to novel datasets and is invariant to the level of sparsity in the data. For our evaluation, we derive a novel dataset from the KITTI benchmark, comprising 93k depth annotated RGB images. Our dataset allows for training and evaluating depth upsampling and depth prediction techniques in challenging real-world settings and will be made available upon publication.

##### Abstract (translated by Google)
在本文中，我们考虑对稀疏输入进行操作的卷积神经网络，以及来自稀疏激光扫描数据的深度上采样的应用。首先，我们证明传统的卷积网络在应用于稀疏数据时性能不佳，即使丢失数据的位置提供给网络。为了克服这个问题，我们提出了一个简单而有效的稀疏卷积层，明确地考虑了卷积运算期间丢失数据的位置。我们在各种基线方法的合成和实际实验中展示了所提出的网络架构的好处。与稠密基线相比，所提出的稀疏卷积网络能够很好地推广到新的数据集，并且对于数据的稀疏性水平是不变的。对于我们的评估，我们从KITTI基准中推导出一个新的数据集，包括93k深度注释的RGB图像。我们的数据集允许在具有挑战性的现实环境中进行深度采样和深度预测技术的培训和评估，并将在发布后提供。

##### URL
[https://arxiv.org/abs/1708.06500](https://arxiv.org/abs/1708.06500)

##### PDF
[https://arxiv.org/pdf/1708.06500](https://arxiv.org/pdf/1708.06500)

