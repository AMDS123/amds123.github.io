---
layout: post
title: "A Unified Approach of Multi-scale Deep and Hand-crafted Features for Defocus Estimation"
date: 2017-04-28 16:16:41
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation CNN
author: Jinsun Park, Yu-Wing Tai, Donghyeon Cho, In So Kweon
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce robust and synergetic hand-crafted features and a simple but efficient deep feature from a convolutional neural network (CNN) architecture for defocus estimation. This paper systematically analyzes the effectiveness of different features, and shows how each feature can compensate for the weaknesses of other features when they are concatenated. For a full defocus map estimation, we extract image patches on strong edges sparsely, after which we use them for deep and hand-crafted feature extraction. In order to reduce the degree of patch-scale dependency, we also propose a multi-scale patch extraction strategy. A sparse defocus map is generated using a neural network classifier followed by a probability-joint bilateral filter. The final defocus map is obtained from the sparse defocus map with guidance from an edge-preserving filtered input image. Experimental results show that our algorithm is superior to state-of-the-art algorithms in terms of defocus estimation. Our work can be used for applications such as segmentation, blur magnification, all-in-focus image generation, and 3-D estimation.

##### Abstract (translated by Google)
在本文中，我们介绍了鲁棒性和协同性的手工特征以及用于离焦估计的卷积神经网络（CNN）体系结构的简单但高效的深度特征。本文系统地分析了不同特征的有效性，并且说明了每个特征在连接时如何弥补其他特征的弱点。对于全散焦图估计，我们在较强的边缘上稀疏地提取图像块，之后我们将它们用于深度和手工特征提取。为了降低斑块尺度依赖程度，我们还提出了一种多尺度斑块提取策略。使用神经网络分类器，然后是概率联合双边滤波器，生成稀疏离焦图。最终的散焦图是从稀疏散焦图中获得的，并且来自边缘保留滤波输入图像的引导。实验结果表明，我们的算法在离焦估计方面优于最先进的算法。我们的工作可以用于分割，模糊放大，全焦点图像生成和3D估计等应用。

##### URL
[https://arxiv.org/abs/1704.08992](https://arxiv.org/abs/1704.08992)

##### PDF
[https://arxiv.org/pdf/1704.08992](https://arxiv.org/pdf/1704.08992)

