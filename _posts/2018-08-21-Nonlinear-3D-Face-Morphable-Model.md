---
layout: post
title: "Nonlinear 3D Face Morphable Model"
date: 2018-08-21 18:14:12
categories: arXiv_CV
tags: arXiv_CV Face
author: Luan Tran, Xiaoming Liu
mathjax: true
---

* content
{:toc}

##### Abstract
As a classic statistical model of 3D facial shape and texture, 3D Morphable Model (3DMM) is widely used in facial analysis, e.g., model fitting, image synthesis. Conventional 3DMM is learned from a set of well-controlled 2D face images with associated 3D face scans, and represented by two sets of PCA basis functions. Due to the type and amount of training data, as well as the linear bases, the representation power of 3DMM can be limited. To address these problems, this paper proposes an innovative framework to learn a nonlinear 3DMM model from a large set of unconstrained face images, without collecting 3D face scans. Specifically, given a face image as input, a network encoder estimates the projection, shape and texture parameters. Two decoders serve as the nonlinear 3DMM to map from the shape and texture parameters to the 3D shape and texture, respectively. With the projection parameter, 3D shape, and texture, a novel analytically-differentiable rendering layer is designed to reconstruct the original input face. The entire network is end-to-end trainable with only weak supervision. We demonstrate the superior representation power of our nonlinear 3DMM over its linear counterpart, and its contribution to face alignment and 3D reconstruction.

##### Abstract (translated by Google)
作为3D面部形状和纹理的经典统计模型，3D可变形模型（3DMM）广泛用于面部分析，例如模型拟合，图像合成。常规3DMM是从一组控制良好的2D面部图像中学习的，其具有相关的3D面部扫描，并由两组PCA基础函数表示。由于训练数据的类型和数量以及线性基础，3DMM的表示能力可能是有限的。为了解决这些问题，本文提出了一种创新框架，用于从大量无约束人脸图像中学习非线性3DMM模型，而无需收集3D人脸扫描。具体地，给定面部图像作为输入，网络编码器估计投影，形状和纹理参数。两个解码器用作非线性3DMM，分别从形状和纹理参数映射到3D形状和纹理。利用投影参数，3D形状和纹理，设计了一种新颖的分析可微分渲染层来重建原始输入面。整个网络是端到端的，只有弱监督才能训练。我们展示了我们的非线性3DMM优于其线性对应物的表现能力，以及它对面部对齐和3D重建的贡献。

##### URL
[http://arxiv.org/abs/1804.03786](http://arxiv.org/abs/1804.03786)

##### PDF
[http://arxiv.org/pdf/1804.03786](http://arxiv.org/pdf/1804.03786)

