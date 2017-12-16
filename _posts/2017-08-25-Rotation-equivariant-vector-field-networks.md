---
layout: post
title: "Rotation equivariant vector field networks"
date: 2017-08-25 12:26:43
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Image_Classification Classification Relation
author: Diego Marcos, Michele Volpi, Nikos Komodakis, Devis Tuia
mathjax: true
---

* content
{:toc}

##### Abstract
In many computer vision tasks, we expect a particular behavior of the output with respect to rotations of the input image. If this relationship is explicitly encoded, instead of treated as any other variation, the complexity of the problem is decreased, leading to a reduction in the size of the required model. In this paper, we propose the Rotation Equivariant Vector Field Networks (RotEqNet), a Convolutional Neural Network (CNN) architecture encoding rotation equivariance, invariance and covariance. Each convolutional filter is applied at multiple orientations and returns a vector field representing magnitude and angle of the highest scoring orientation at every spatial location. We develop a modified convolution operator relying on this representation to obtain deep architectures. We test RotEqNet on several problems requiring different responses with respect to the inputs' rotation: image classification, biomedical image segmentation, orientation estimation and patch matching. In all cases, we show that RotEqNet offers extremely compact models in terms of number of parameters and provides results in line to those of networks orders of magnitude larger.

##### Abstract (translated by Google)
在许多计算机视觉任务中，我们期望输出的特定行为与输入图像的旋转有关。如果这种关系是明确编码的，而不是被视为任何其他变化，那么问题的复杂性就会降低，从而导致所需模型的规模缩小。在本文中，我们提出旋转等变矢量场网络（RotEqNet），卷积神经网络（CNN）架构编码旋转等式，不变性和协方差。每个卷积滤波器被应用在多个方向上，并且返回表示每个空间位置处的最高得分方向的幅度和角度的矢量场。我们依靠这种表示方法开发一个修改的卷积算子来获得深层结构。我们测试RotEqNet的几个问题需要对输入的旋转不同的反应：图像分类，生物医学图像分割，方向估计和补丁匹配。在所有情况下，我们都表明，RotEqNet提供了极其紧凑的参数数量模型，并提供了与网络数量级更大的结果一致的结果。

##### URL
[https://arxiv.org/abs/1612.09346](https://arxiv.org/abs/1612.09346)

##### PDF
[https://arxiv.org/pdf/1612.09346](https://arxiv.org/pdf/1612.09346)

