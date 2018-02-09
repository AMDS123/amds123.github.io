---
layout: post
title: "An Unsupervised Learning Model for Deformable Medical Image Registration"
date: 2018-02-07 19:23:57
categories: arXiv_CV
tags: arXiv_CV
author: Guha Balakrishnan, Amy Zhao, Mert R. Sabuncu, John Guttag, Adrian V. Dalca
mathjax: true
---

* content
{:toc}

##### Abstract
We present an efficient learning-based algorithm for deformable, pairwise 3D medical image registration. Current registration methods optimize an energy function independently for each pair of images, which can be time-consuming for large data. We define registration as a parametric function, and optimize its parameters given a set of images from a collection of interest. Given a new pair of scans, we can quickly compute a registration field by directly evaluating the function using the learned parameters. We model this function using a CNN, and use a spatial transform layer to reconstruct one image from another while imposing smoothness constraints on the registration field. The proposed method does not require supervised information such as ground truth registration fields or anatomical landmarks. We demonstrate registration accuracy comparable to state-of-the-art 3D image registration, while operating orders of magnitude faster in practice. Our method promises to significantly speed up medical image analysis and processing pipelines, while facilitating novel directions in learning-based registration and its applications. Our code is available at https://github.com/balakg/voxelmorph.

##### Abstract (translated by Google)
我们提出了一个高效的基于学习的算法可变形，成对三维医学图像配准。当前的配准方法针对每对图像独立地优化能量函数，这对于大数据可能是耗时的。我们将注册定义为一个参数函数，并且从一组感兴趣的集合中给出一组图像来优化其参数。给定一对新的扫描，我们可以通过使用学习的参数直接评估函数来快速计算注册字段。我们使用CNN对这个函数进行建模，并且在注册字段上施加平滑约束的同时，使用空间变换层重建另一个图像。所提出的方法不需要监督信息，如地面实况注册领域或解剖标志。我们证明了与国家最先进的三维图像配准相媲美的配准精度，同时在实践中运行速度更快。我们的方法有望显着加快医学图像分析和处理流程，同时促进基于学习的注册及其应用的新方向。我们的代码可以在https://github.com/balakg/voxelmorph。

##### URL
[http://arxiv.org/abs/1802.02604](http://arxiv.org/abs/1802.02604)

##### PDF
[http://arxiv.org/pdf/1802.02604](http://arxiv.org/pdf/1802.02604)

