---
layout: post
title: "VoxelMorph: A Learning Framework for Deformable Medical Image Registration"
date: 2018-09-14 02:46:16
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Guha Balakrishnan, Amy Zhao, Mert R. Sabuncu, John Guttag, Adrian V. Dalca
mathjax: true
---

* content
{:toc}

##### Abstract
We present VoxelMorph, a fast, unsupervised, learning-based algorithm for deformable pairwise medical image registration. Traditional registration methods optimize an objective function independently for each pair of images, which is time-consuming for large datasets. We define registration as a parametric function, implemented as a convolutional neural network (CNN). We optimize its global parameters given a set of images from a collection of interest. Given a new pair of scans, VoxelMorph rapidly computes a deformation field by directly evaluating the function. Our model is flexible, enabling the use of any differentiable objective function to optimize these parameters. In this work, we propose and extensively evaluate a standard image matching objective function as well as an objective function that can use auxiliary data such as anatomical segmentations available only at training time. We demonstrate that the unsupervised model's accuracy is comparable to state-of-the-art methods, while operating orders of magnitude faster. We also show that VoxelMorph trained with auxiliary data significantly improves registration accuracy at test time. Our method promises to significantly speed up medical image analysis and processing pipelines, while facilitating novel directions in learning-based registration and its applications. Our code is freely available at voxelmorph.csail.mit.edu.

##### Abstract (translated by Google)
我们提出了VoxelMorph，一种快速，无监督，基于学习的可变形成对医学图像配准算法。传统的配准方法针对每对图像独立地优化目标函数，这对于大型数据集来说是耗时的。我们将配准定义为参数函数，实现为卷积神经网络（CNN）。我们根据感兴趣的集合中的一组图像优化其全局参数。给定一对新的扫描，VoxelMorph通过直接评估函数来快速计算变形场。我们的模型非常灵活，可以使用任何可微分的目标函数来优化这些参数。在这项工作中，我们提出并广泛评估标准图像匹配目标函数以及可以使用辅助数据的目标函数，例如仅在训练时可用的解剖分割。我们证明无监督模型的精确度与最先进的方法相当，而操作数量级更快。我们还表明，使用辅助数据训练的VoxelMorph显着提高了测试时的配准精度。我们的方法有望显着加速医学图像分析和处理管道，同时促进基于学习的注册及其应用的新方向。我们的代码可以在voxelmorph.csail.mit.edu免费获得。

##### URL
[http://arxiv.org/abs/1809.05231](http://arxiv.org/abs/1809.05231)

##### PDF
[http://arxiv.org/pdf/1809.05231](http://arxiv.org/pdf/1809.05231)

