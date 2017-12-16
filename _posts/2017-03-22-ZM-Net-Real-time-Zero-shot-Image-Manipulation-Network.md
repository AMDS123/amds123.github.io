---
layout: post
title: "ZM-Net: Real-time Zero-shot Image Manipulation Network"
date: 2017-03-22 17:08:40
categories: arXiv_CV
tags: arXiv_CV Style_Transfer
author: Hao Wang, Xiaodan Liang, Hao Zhang, Dit-Yan Yeung, Eric P. Xing
mathjax: true
---

* content
{:toc}

##### Abstract
Many problems in image processing and computer vision (e.g. colorization, style transfer) can be posed as 'manipulating' an input image into a corresponding output image given a user-specified guiding signal. A holy-grail solution towards generic image manipulation should be able to efficiently alter an input image with any personalized signals (even signals unseen during training), such as diverse paintings and arbitrary descriptive attributes. However, existing methods are either inefficient to simultaneously process multiple signals (let alone generalize to unseen signals), or unable to handle signals from other modalities. In this paper, we make the first attempt to address the zero-shot image manipulation task. We cast this problem as manipulating an input image according to a parametric model whose key parameters can be conditionally generated from any guiding signal (even unseen ones). To this end, we propose the Zero-shot Manipulation Net (ZM-Net), a fully-differentiable architecture that jointly optimizes an image-transformation network (TNet) and a parameter network (PNet). The PNet learns to generate key transformation parameters for the TNet given any guiding signal while the TNet performs fast zero-shot image manipulation according to both signal-dependent parameters from the PNet and signal-invariant parameters from the TNet itself. Extensive experiments show that our ZM-Net can perform high-quality image manipulation conditioned on different forms of guiding signals (e.g. style images and attributes) in real-time (tens of milliseconds per image) even for unseen signals. Moreover, a large-scale style dataset with over 20,000 style images is also constructed to promote further research.

##### Abstract (translated by Google)
在给定用户指定的引导信号的情况下，图像处理和计算机视觉（例如，着色，样式转移）中的许多问题可以被设置为将输入图像“操纵”成对应的输出图像。针对通用图像处理的圣杯解决方案应该能够利用任何个性化信号（甚至在训练期间看不见的信号）有效地改变输入图像，例如不同的绘画和任意的描述性属性。然而，现有的方法要么同时处理多个信号（更不用说推广到看不见的信号），要么不能处理来自其他模式的信号。在本文中，我们首先尝试解决零镜头图像处理任务。我们把这个问题作为一个输入图像根据一个参数模型来操作，其参数模型的关键参数可以从任何指导信号（甚至看不见的）有条件地生成。为此，我们提出了零映射操作网（Zero-Shot Manipulation Net，ZM-Net），这是一个完全可微的架构，共同优化了图像转换网络（TNet）和参数网络（PNet）。 PNet学习根据来自PNet的信号相关参数和来自TNet自身的信号不变参数，在给定任何指导信号的情况下，为TNet生成关键变换参数，而TNet执行快速零镜头图像操作。大量的实验表明，即使对于看不见的信号，我们的ZM-Net也可以对不同形式的指导信号（例如风格图像和属性）进行实时（每幅图像几十毫秒）的高质量图像处理。此外，还构建了一个超过20000个风格图像的大型风格数据集，以促进进一步的研究。

##### URL
[https://arxiv.org/abs/1703.07255](https://arxiv.org/abs/1703.07255)

##### PDF
[https://arxiv.org/pdf/1703.07255](https://arxiv.org/pdf/1703.07255)

