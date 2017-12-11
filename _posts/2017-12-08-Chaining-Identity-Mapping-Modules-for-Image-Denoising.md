---
layout: post
title: "Chaining Identity Mapping Modules for Image Denoising"
date: 2017-12-08 03:51:54
categories: arXiv_CV
tags: arXiv_CV CNN
author: Saeed Anwar, Cong Phouc Huynh, Fatih Porikli
mathjax: true
---

* content
{:toc}

##### Abstract
We propose to learn a fully-convolutional network model that consists of a Chain of Identity Mapping Modules (CIMM) for image denoising. The CIMM structure possesses two distinctive features that are important for the noise removal task. Firstly, each residual unit employs identity mappings as the skip connections and receives pre-activated input in order to preserve the gradient magnitude propagated in both the forward and backward directions. Secondly, by utilizing dilated kernels for the convolution layers in the residual branch, in other words within an identity mapping module, each neuron in the last convolution layer can observe the full receptive field of the first layer. After being trained on the BSD400 dataset, the proposed network produces remarkably higher numerical accuracy and better visual image quality than the state-of-the-art when being evaluated on conventional benchmark images and the BSD68 dataset.

##### Abstract (translated by Google)
我们建议学习一个完全卷积网络模型，由一个用于图像去噪的身份映射模块（CIMM）组成。 CIMM结构具有两个对噪声消除任务重要的独特特征。首先，每个剩余单元采用身份映射作为跳过连接，并接收预激活的输入，以保持在向前和向后方向传播的梯度幅度。其次，通过对残差分支中的卷积层，换句话说，在身份映射模块中利用扩张核心，最后一个卷积层中的每个神经元可以观察到第一层的完整感受野。在对BSD400数据集进行训练之后，所提出的网络在对传统基准图像和BSD68数据集进行评估时产生比现有技术更高的数字精度和更好的视觉图像质量。

##### URL
[http://arxiv.org/abs/1712.02933](http://arxiv.org/abs/1712.02933)

##### PDF
[http://arxiv.org/pdf/1712.02933](http://arxiv.org/pdf/1712.02933)

