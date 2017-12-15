---
layout: post
title: "3D U-Net: Learning Dense Volumetric Segmentation from Sparse Annotation"
date: 2016-06-21 16:42:20
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation
author: Özgün Çiçek, Ahmed Abdulkadir, Soeren S. Lienkamp, Thomas Brox, Olaf Ronneberger
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a network for volumetric segmentation that learns from sparsely annotated volumetric images. We outline two attractive use cases of this method: (1) In a semi-automated setup, the user annotates some slices in the volume to be segmented. The network learns from these sparse annotations and provides a dense 3D segmentation. (2) In a fully-automated setup, we assume that a representative, sparsely annotated training set exists. Trained on this data set, the network densely segments new volumetric images. The proposed network extends the previous u-net architecture from Ronneberger et al. by replacing all 2D operations with their 3D counterparts. The implementation performs on-the-fly elastic deformations for efficient data augmentation during training. It is trained end-to-end from scratch, i.e., no pre-trained network is required. We test the performance of the proposed method on a complex, highly variable 3D structure, the Xenopus kidney, and achieve good results for both use cases.

##### Abstract (translated by Google)
本文介绍了一个网络的体积分割学习稀疏注释的体积图像。我们概述了这种方法的两个有吸引力的用例：（1）在半自动设置中，用户注释卷中的一些片段以进行分段。网络从这些稀疏注释中学习并提供密集的3D分割。 （2）在全自动设置中，我们假定存在代表性的，稀疏注释的训练集。在这个数据集训练，网络密集分割新的体积图像。所提出的网络扩展了Ronneberger等人以前的u-net架构。通过替换所有的2D操作与他们的3D对应。这个实现可以在训练过程中实现有效的数据增强的即时弹性变形。它从头开始被端对端训练，即不需要预先训练的网络。我们在一个复杂的，高度可变的三维结构Xenopus肾脏上测试了所提出的方法的性能，并且在两种用例中都取得了很好的结果。

##### URL
[https://arxiv.org/abs/1606.06650](https://arxiv.org/abs/1606.06650)

##### PDF
[https://arxiv.org/pdf/1606.06650](https://arxiv.org/pdf/1606.06650)

