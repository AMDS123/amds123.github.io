---
layout: post
title: "Efficient Fusion of Sparse and Complementary Convolutions for Object Recognition and Detection"
date: 2018-08-07 00:39:56
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse CNN Image_Classification Classification Detection Recognition
author: Chun-Fu (Richard) Chen, Quanfu Fan, Marco Pistoia, Gwo Giun (Chris)Lee
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new method for exploiting sparsity in convolutional kernels to create compact and computationally efficient convolutional neural networks (CNNs). Our approach is based on hand-crafted sparse kernels that are spatially complementary, allowing for an effective combination of them to represent more complex but discriminative kernels in an efficient way. Based on this, we develop a module that can be used to replace a convolutional kernel of any size greater than 1. We integrate such a module into various existing CNN models and conduct extensive experiments to demonstrate the effectiveness of our proposed approach on image classification as well as object localization and detection. The experiments validate the adaptability of the proposed method. For classification and localization, the proposed approach achieves competitive or better performance than the baselines and related works for various networks while providing lower computational costs and fewer parameters (on average, a $2-3\times$ reduction of convolutional parameters and a $2-4\times$ speedup in computation). On the other hand, our approach leads to a VGG16-based Faster RCNN detector that is 12.4$\times$ smaller and about 3$\times$ faster than the baseline.

##### Abstract (translated by Google)
我们提出了一种利用卷积核中的稀疏性来创建紧凑且计算上有效的卷积神经网络（CNN）的新方法。我们的方法基于手工制作的稀疏内核，这些内核在空间上是互补的，允许它们的有效组合以有效的方式表示更复杂但有区别的内核。基于此，我们开发了一个模块，可用于替换任何大小超过1的卷积核。我们将这样的模块集成到各种现有的CNN模型中并进行大量实验，以证明我们提出的方法在图像分类方面的有效性。以及对象定位和检测。实验验证了该方法的适应性。对于分类和本地化，所提出的方法比各种网络的基线和相关工作实现了竞争性或更好的性能，同时提供更低的计算成本和更少的参数（平均而言，卷积参数减少$ 2-3 \ $ $和$ 2-4 \ times $计算加速）。另一方面，我们的方法导致基于VGG16的更快的RCNN探测器，比基线小12.4美元，比基线快3美元。

##### URL
[http://arxiv.org/abs/1808.02167](http://arxiv.org/abs/1808.02167)

##### PDF
[http://arxiv.org/pdf/1808.02167](http://arxiv.org/pdf/1808.02167)

