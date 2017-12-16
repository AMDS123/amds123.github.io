---
layout: post
title: "Optimal Multi-Object Segmentation with Novel Gradient Vector Flow Based Shape Priors"
date: 2017-05-22 15:33:39
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Junjie Bai, Abhay Shah, Xiaodong Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Shape priors have been widely utilized in medical image segmentation to improve segmentation accuracy and robustness. A major way to encode such a prior shape model is to use a mesh representation, which is prone to causing self-intersection or mesh folding. Those problems require complex and expensive algorithms to mitigate. In this paper, we propose a novel shape prior directly embedded in the voxel grid space, based on gradient vector flows of a pre-segmentation. The flexible and powerful prior shape representation is ready to be extended to simultaneously segmenting multiple interacting objects with minimum separation distance constraint. The problem is formulated as a Markov random field problem whose exact solution can be efficiently computed with a single minimum s-t cut in an appropriately constructed graph. The proposed algorithm is validated on two multi-object segmentation applications: the brain tissue segmentation in MRI images, and the bladder/prostate segmentation in CT images. Both sets of experiments show superior or competitive performance of the proposed method to other state-of-the-art methods.

##### Abstract (translated by Google)
形状先验已被广泛应用于医学图像分割，以提高分割的准确性和鲁棒性。编码这种先前的形状模型的主要方式是使用网格表示，其容易导致自相交或网格折叠。这些问题需要复杂而昂贵的算法来减轻。在本文中，我们基于预分割的梯度矢量流，提出了一种直接嵌入在体素网格空间中的新形状。灵活而强大的先前形状表示已经准备好被扩展，以同时分割多个相互作用的对象，并且具有最小的间隔距离约束。该问题被表述为马尔可夫随机场问题，其精确解可以在适当构造的图中用单个最小s-t切割来有效计算。所提出的算法在两个多目标分割应用上得到验证：MRI图像中的脑组织分割和CT图像中的膀胱/前列腺分割。两套实验都表明所提出的方法对其他最先进的方法具有优越的或有竞争力的性能。

##### URL
[https://arxiv.org/abs/1705.10311](https://arxiv.org/abs/1705.10311)

##### PDF
[https://arxiv.org/pdf/1705.10311](https://arxiv.org/pdf/1705.10311)

