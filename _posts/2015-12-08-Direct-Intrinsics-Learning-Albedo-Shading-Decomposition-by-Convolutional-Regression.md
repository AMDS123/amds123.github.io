---
layout: post
title: "Direct Intrinsics: Learning Albedo-Shading Decomposition by Convolutional Regression"
date: 2015-12-08 03:38:52
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Takuya Narihira, Michael Maire, Stella X. Yu
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a new approach to intrinsic image decomposition, the task of decomposing a single image into albedo and shading components. Our strategy, which we term direct intrinsics, is to learn a convolutional neural network (CNN) that directly predicts output albedo and shading channels from an input RGB image patch. Direct intrinsics is a departure from classical techniques for intrinsic image decomposition, which typically rely on physically-motivated priors and graph-based inference algorithms. The large-scale synthetic ground-truth of the MPI Sintel dataset plays a key role in training direct intrinsics. We demonstrate results on both the synthetic images of Sintel and the real images of the classic MIT intrinsic image dataset. On Sintel, direct intrinsics, using only RGB input, outperforms all prior work, including methods that rely on RGB+Depth input. Direct intrinsics also generalizes across modalities; it produces quite reasonable decompositions on the real images of the MIT dataset. Our results indicate that the marriage of CNNs with synthetic training data may be a powerful new technique for tackling classic problems in computer vision.

##### Abstract (translated by Google)
我们引入了一种新的内在图像分解方法，即将单个图像分解为反照率和阴影分量的任务。我们称为直接内在函数的策略是学习一个卷积神经网络（CNN），它直接从输入的RGB图像块预测输出反照率和阴影通道。直接内在是离开古典技术的固有图像分解，这通常依赖于物理动机的先验和基于图形的推理算法。 MPI Sintel数据集的大规模合成基础真实性在训练直接内在函数中起着关键作用。我们在Sintel的合成图像和经典的MIT本征图像数据集的真实图像上展示结果。在Sintel上，仅使用RGB输入的直接内在函数优于以前的所有工作，包括依赖于RGB +深度输入的方法。直接内在性也泛化于各种形式中;它对MIT数据集的真实图像进行了相当合理的分解。我们的结果表明CNNs与综合训练数据的结合可能是解决计算机视觉中的经典问题的一种强大的新技术。

##### URL
[https://arxiv.org/abs/1512.02311](https://arxiv.org/abs/1512.02311)

##### PDF
[https://arxiv.org/pdf/1512.02311](https://arxiv.org/pdf/1512.02311)

