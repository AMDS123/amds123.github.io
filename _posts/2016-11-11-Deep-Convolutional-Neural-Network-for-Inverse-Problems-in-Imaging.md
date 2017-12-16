---
layout: post
title: "Deep Convolutional Neural Network for Inverse Problems in Imaging"
date: 2016-11-11 12:35:08
categories: arXiv_CV
tags: arXiv_CV Sparse CNN
author: Kyong Hwan Jin, Michael T. McCann, Emmanuel Froustey, Michael Unser
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel deep convolutional neural network (CNN)-based algorithm for solving ill-posed inverse problems. Regularized iterative algorithms have emerged as the standard approach to ill-posed inverse problems in the past few decades. These methods produce excellent results, but can be challenging to deploy in practice due to factors including the high computational cost of the forward and adjoint operators and the difficulty of hyper parameter selection. The starting point of our work is the observation that unrolled iterative methods have the form of a CNN (filtering followed by point-wise non-linearity) when the normal operator (H*H, the adjoint of H times H) of the forward model is a convolution. Based on this observation, we propose using direct inversion followed by a CNN to solve normal-convolutional inverse problems. The direct inversion encapsulates the physical model of the system, but leads to artifacts when the problem is ill-posed; the CNN combines multiresolution decomposition and residual learning in order to learn to remove these artifacts while preserving image structure. We demonstrate the performance of the proposed network in sparse-view reconstruction (down to 50 views) on parallel beam X-ray computed tomography in synthetic phantoms as well as in real experimental sinograms. The proposed network outperforms total variation-regularized iterative reconstruction for the more realistic phantoms and requires less than a second to reconstruct a 512 x 512 image on GPU.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的基于深度卷积神经网络（CNN）的算法来解决不适定的逆问题。正规化迭代算法已经成为过去几十年中不适定反演问题的标准方法。这些方法产生了很好的结果，但由于前向和伴随算子的高计算成本以及超参数选择的困难等因素，在实际中可能会面临挑战。我们工作的出发点是当前向模型的正规算子（H * H，H次H的伴随）时，展开的迭代方法具有CNN的形式（滤波后面跟着点的非线性）是一个卷积。基于这个观察，我们建议使用直接反演，然后用CNN来求解正常卷积逆问题。直接反演封装了系统的物理模型，但是当问题不适当时会导致伪造; CNN将多分辨率分解和残差学习相结合，以便在保留图像结构的同时学习去除这些伪像。我们在合成体模的平行束X射线计算机断层扫描以及实际的实验正弦图中展示了所提出的网络在稀疏视图重建（低至50个视图）方面的性能。所提出的网络优于用于更现实幻像的总变异规则化迭代重构，并且在GPU上重建512×512图像需要不到一秒的时间。

##### URL
[https://arxiv.org/abs/1611.03679](https://arxiv.org/abs/1611.03679)

##### PDF
[https://arxiv.org/pdf/1611.03679](https://arxiv.org/pdf/1611.03679)

