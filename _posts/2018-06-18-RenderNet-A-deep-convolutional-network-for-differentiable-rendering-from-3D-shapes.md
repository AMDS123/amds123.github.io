---
layout: post
title: "RenderNet: A deep convolutional network for differentiable rendering from 3D shapes"
date: 2018-06-18 09:45:33
categories: arXiv_CV
tags: arXiv_CV CNN
author: Thu Nguyen-Phuoc, Chuan Li, Stephen Balaban, Yongliang Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional computer graphics rendering pipeline is designed for procedurally generating 2D quality images from 3D shapes with high performance. The non-differentiability due to discrete operations such as visibility computation makes it hard to explicitly correlate rendering parameters and the resulting image, posing a significant challenge for inverse rendering tasks. Recent work on differentiable rendering achieves differentiability either by designing surrogate gradients for non-differentiable operations or via an approximate but differentiable renderer. These methods, however, are still limited when it comes to handling occlusion, and restricted to particular rendering effects. We present RenderNet, a differentiable rendering convolutional network with a novel projection unit that can render 2D images from 3D shapes. Spatial occlusion and shading calculation are automatically encoded in the network. Our experiments show that RenderNet can successfully learn to implement different shaders, and can be used in inverse rendering tasks to estimate shape, pose, lighting and texture from a single image.

##### Abstract (translated by Google)
传统的计算机图形渲染管线设计用于以高性能从3D形状中程序化地生成2D质量图像。由于诸如可视性计算之类的离散操作导致的非可微分性使得很难明确地关联渲染参数和所得到的图像，这对于反演渲染任务构成了重大挑战。最近有关可微分渲染的工作通过为不可微分操作设计替代梯度或通过近似但可区分的渲染器实现可微分性。然而，这些方法在处理遮挡时仍然有限，并且仅限于特定的渲染效果。我们提出了RenderNet，一种可以渲染二维图像的新颖投影单元的可微分渲染卷积网络。空间遮挡和阴影计算在网络中自动编码。我们的实验表明，RenderNet可以成功地学习实现不同的着色器，并且可以用于逆向渲染任务，以从单个图像估计形状，姿态，光照和纹理。

##### URL
[http://arxiv.org/abs/1806.06575](http://arxiv.org/abs/1806.06575)

##### PDF
[http://arxiv.org/pdf/1806.06575](http://arxiv.org/pdf/1806.06575)

