---
layout: post
title: "On Learning 3D Face Morphable Model from In-the-wild Images"
date: 2018-08-28 22:25:01
categories: arXiv_CV
tags: arXiv_CV Face
author: Luan Tran, Xiaoming Liu
mathjax: true
---

* content
{:toc}

##### Abstract
As a classic statistical model of 3D facial shape and albedo, 3D Morphable Model (3DMM) is widely used in facial analysis, e.g., model fitting, image synthesis. Conventional 3DMM is learned from a set of 3D face scans with associated well-controlled 2D face images, and represented by two sets of PCA basis functions. Due to the type and amount of training data, as well as, the linear bases, the representation power of 3DMM can be limited. To address these problems, this paper proposes an innovative framework to learn a nonlinear 3DMM model from a large set of in-the-wild face images, without collecting 3D face scans. Specifically, given a face image as input, a network encoder estimates the projection, lighting, shape and albedo parameters. Two decoders serve as the nonlinear 3DMM to map from the shape and albedo parameters to the 3D shape and albedo, respectively. With the projection parameter, lighting, 3D shape, and albedo, a novel analytically-differentiable rendering layer is designed to reconstruct the original input face. The entire network is end-to-end trainable with only weak supervision. We demonstrate the superior representation power of our nonlinear 3DMM over its linear counterpart, and its contribution to face alignment, 3D reconstruction, and face editing.

##### Abstract (translated by Google)
作为3D面部形状和反照率的经典统计模型，3D变形模型（3DMM）广泛用于面部分析，例如模型拟合，图像合成。常规3DMM是从具有相关的良好控制的2D面部图像的一组3D面部扫描中学习的，并且由两组PCA基础函数表示。由于训练数据的类型和数量以及线性基础，3DMM的表示能力可能是有限的。为了解决这些问题，本文提出了一种创新框架，用于从大量野外人脸图像中学习非线性3DMM模型，而无需收集3D人脸扫描。具体地，给定面部图像作为输入，网络编码器估计投影，光照，形状和反照率参数。两个解码器用作非线性3DMM，分别从形状和反照率参数映射到3D形状和反照率。利用投影参数，光照，3D形状和反照率，设计了一种新颖的分析可微分渲染层来重建原始输入面。整个网络是端到端的，只有弱监督才能训练。我们展示了我们的非线性3DMM优于其线性对应物的表现能力，以及它对面部对齐，3D重建和面部编辑的贡献。

##### URL
[http://arxiv.org/abs/1808.09560](http://arxiv.org/abs/1808.09560)

##### PDF
[http://arxiv.org/pdf/1808.09560](http://arxiv.org/pdf/1808.09560)

