---
layout: post
title: "Multi-style Generative Network for Real-time Transfer"
date: 2017-11-16 19:38:35
categories: arXiv_CV
tags: arXiv_CV Style_Transfer Embedding
author: Hang Zhang, Kristin Dana
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the rapid progress in style transfer, existing approaches using feed-forward generative network for multi-style or arbitrary-style transfer are usually compromised of image quality and model flexibility. We find it is fundamentally difficult to achieve comprehensive style modeling using 1-dimensional style embedding. Motivated by this, we introduce CoMatch Layer that learns to match the second order feature statistics with the target styles. With the CoMatch Layer, we build a Multi-style Generative Network (MSG-Net), which achieves real-time performance. We also employ an specific strategy of upsampled convolution which avoids checkerboard artifacts caused by fractionally-strided convolution. Our method has achieved superior image quality comparing to state-of-the-art approaches. The proposed MSG-Net as a general approach for real-time style transfer is compatible with most existing techniques including content-style interpolation, color-preserving, spatial control and brush stroke size control. MSG-Net is the first to achieve real-time brush-size control in a purely feed-forward manner for style transfer. Our implementations and pre-trained models for Torch, PyTorch and MXNet frameworks will be publicly available.

##### Abstract (translated by Google)
尽管样式转换方面取得了快速的进展，但现有的使用前馈生成网络进行多样式或任意样式转换的方法通常会降低图像质量和模型灵活性。我们发现使用一维样式嵌入来实现全面的样式建模从根本上是困难的。为此，我们引入CoMatch Layer来学习匹配目标样式的二阶特征统计。通过CoMatch Layer，我们构建了一个多样式的生成网络（MSG-Net），实现了实时性能。我们还采用上采样卷积的特定策略来避免分数阶卷积引起的棋盘伪影。与最先进的方法相比，我们的方法已经实现了卓越的图像质量。所提出的MSG-Net作为实时样式转换的一般方法与大多数现有技术兼容，包括内容式内插，颜色保持，空间控制和画笔笔画大小控制。 MSG-Net是第一个以纯前馈方式实现实时画笔大小控制的样式转换。我们的Torch，PyTorch和MXNet框架的实施和预训练模型将公开发布。

##### URL
[https://arxiv.org/abs/1703.06953](https://arxiv.org/abs/1703.06953)

##### PDF
[https://arxiv.org/pdf/1703.06953](https://arxiv.org/pdf/1703.06953)

