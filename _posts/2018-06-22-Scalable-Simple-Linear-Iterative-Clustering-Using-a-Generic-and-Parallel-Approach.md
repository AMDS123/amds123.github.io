---
layout: post
title: "Scalable Simple Linear Iterative Clustering Using a Generic and Parallel Approach"
date: 2018-06-22 16:02:44
categories: arXiv_CV
tags: arXiv_CV Segmentation Deep_Learning Quantitative
author: Bradley C. Lowekamp, David T. Chen, Ziv Yaniv, Terry S. Yoo
mathjax: true
---

* content
{:toc}

##### Abstract
Superpixel algorithms have proven to be a useful initial step for segmentation and subsequent processing of images, reducing computational complexity by replacing the use of expensive per-pixel primitives with a higher-level abstraction, superpixels. They have been successfully applied both in the context of traditional image analysis and deep learning based approaches. In this work, we present a generalized implementation of the simple linear iterative clustering (SLIC) superpixel algorithm that has been generalized for n-dimensional scalar and multi-channel images. Additionally, the standard iterative implementation is replaced by a parallel, multi-threaded one. We describe the implementation details and analyze its scalability using a strong scaling formulation. Quantitative evaluation is performed using a 3D image, the Visible Human cryosection dataset, and a 2D image from the same dataset. Results show good scalability with runtime gains even when using a large number of threads that exceeds the physical number of available cores (hyperthreading).

##### Abstract (translated by Google)
超像素算法已被证明是图像分割和后续处理的一个有用的初始步骤，通过用更高级别的抽象（超像素）代替使用昂贵的每像素基元来降低计算复杂性。它们已经成功应用于传统图像分析和基于深度学习的方法。在这项工作中，我们提出了一种广义实现的简单线性迭代聚类（SLIC）超像素算法，该算法已被推广用于n维标量和多通道图像。此外，标准的迭代实现被一个并行的多线程代替。我们描述实现细节并使用强大的缩放公式分析其可伸缩性。使用3D图像，可见人体冷冻切片数据集和来自相同数据集的2D图像进行定量评估。即使使用大量超过可用内核物理数量的线程（超线程），结果也显示出良好的可伸缩性和运行时增益。

##### URL
[http://arxiv.org/abs/1806.08741](http://arxiv.org/abs/1806.08741)

##### PDF
[http://arxiv.org/pdf/1806.08741](http://arxiv.org/pdf/1806.08741)

