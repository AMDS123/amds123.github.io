---
layout: post
title: "ATGV-Net: Accurate Depth Super-Resolution"
date: 2016-07-27 07:29:08
categories: arXiv_CV
tags: arXiv_CV Regularization Super_Resolution CNN Optimization
author: Gernot Riegler, Matthias Rüther, Horst Bischof
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we present a novel approach for single depth map super-resolution. Modern consumer depth sensors, especially Time-of-Flight sensors, produce dense depth measurements, but are affected by noise and have a low lateral resolution. We propose a method that combines the benefits of recent advances in machine learning based single image super-resolution, i.e. deep convolutional networks, with a variational method to recover accurate high-resolution depth maps. In particular, we integrate a variational method that models the piecewise affine structures apparent in depth data via an anisotropic total generalized variation regularization term on top of a deep network. We call our method ATGV-Net and train it end-to-end by unrolling the optimization procedure of the variational method. To train deep networks, a large corpus of training data with accurate ground-truth is required. We demonstrate that it is feasible to train our method solely on synthetic data that we generate in large quantities for this task. Our evaluations show that we achieve state-of-the-art results on three different benchmarks, as well as on a challenging Time-of-Flight dataset, all without utilizing an additional intensity image as guidance.

##### Abstract (translated by Google)
在这项工作中，我们提出了一个单一的深度图超分辨率的新方法。现代消费者深度传感器，特别是飞行时间传感器，产生密集的深度测量结果，但受到噪音的影响，横向分辨率低。我们提出了一种方法，将基于机器学习的单幅图像超分辨率（即深度卷积网络）的最新进展的优点与用于恢复精确的高分辨率深度图的变分方法相结合。特别是，我们整合了一个变分方法，通过在深度网络顶部的各向异性全广义变化正则化项，对深度数据中明显的分段仿射结构进行建模。我们称之为ATGV-Net方法，通过展开变分法的优化程序来对它进行端到端的训练。为了训练深度网络，需要大量准确的基础真实的训练数据。我们证明，我们的方法仅仅是针对这项任务大量生成的合成数据进行训练是可行的。我们的评估显示，我们在三个不同的基准以及具有挑战性的飞行时间数据集上实现了最新的结果，所有这些都没有使用额外的强度图像作为指导。

##### URL
[https://arxiv.org/abs/1607.07988](https://arxiv.org/abs/1607.07988)

##### PDF
[https://arxiv.org/pdf/1607.07988](https://arxiv.org/pdf/1607.07988)

