---
layout: post
title: "Human Action Recognition using Factorized Spatio-Temporal Convolutional Networks"
date: 2015-10-02 11:24:04
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Image_Classification Inference Classification Recognition
author: Lin Sun, Kui Jia, Dit-Yan Yeung, Bertram E. Shi
mathjax: true
---

* content
{:toc}

##### Abstract
Human actions in video sequences are three-dimensional (3D) spatio-temporal signals characterizing both the visual appearance and motion dynamics of the involved humans and objects. Inspired by the success of convolutional neural networks (CNN) for image classification, recent attempts have been made to learn 3D CNNs for recognizing human actions in videos. However, partly due to the high complexity of training 3D convolution kernels and the need for large quantities of training videos, only limited success has been reported. This has triggered us to investigate in this paper a new deep architecture which can handle 3D signals more effectively. Specifically, we propose factorized spatio-temporal convolutional networks (FstCN) that factorize the original 3D convolution kernel learning as a sequential process of learning 2D spatial kernels in the lower layers (called spatial convolutional layers), followed by learning 1D temporal kernels in the upper layers (called temporal convolutional layers). We introduce a novel transformation and permutation operator to make factorization in FstCN possible. Moreover, to address the issue of sequence alignment, we propose an effective training and inference strategy based on sampling multiple video clips from a given action video sequence. We have tested FstCN on two commonly used benchmark datasets (UCF-101 and HMDB-51). Without using auxiliary training videos to boost the performance, FstCN outperforms existing CNN based methods and achieves comparable performance with a recent method that benefits from using auxiliary training videos.

##### Abstract (translated by Google)
视频序列中的人类行为是三维（3D）时空信号，其表征所涉及的人和物体的视觉外观和动作动态。受到用于图像分类的卷积神经网络（CNN）的成功的启发，近来已经尝试学习用于识别视频中的人类动作的3D CNN。但是，部分原因是由于培训3D卷积核的高复杂性以及大量训练视频的需要，仅有有限的成功报道。这引发了我们在本文中研究一种能够更有效地处理3D信号的新的深层架构。具体而言，我们提出将因特网化的时空卷积网络（FSTCN）分解为原始三维卷积核学习，作为在较低层（称为空间卷积层）中学习二维空间核的顺序过程，然后学习上层的一维时间核层（称为时间卷积层）。我们引入了一个新的转换和排列算子，使得FstCN中的分解成为可能。此外，为了解决序列对齐的问题，我们提出了一个有效的训练和推理策略，基于从给定的动作视频序列中抽取多个视频片段。我们已经在两个常用的基准数据集（UCF-101和HMDB-51）上测试了FstCN。如果不使用辅助培训视频来提升性能，FstCN将优于现有的基于CNN的方法，并且可以实现与使用辅助培训视频所带来的最新方法相媲美的性能。

##### URL
[https://arxiv.org/abs/1510.00562](https://arxiv.org/abs/1510.00562)

##### PDF
[https://arxiv.org/pdf/1510.00562](https://arxiv.org/pdf/1510.00562)

