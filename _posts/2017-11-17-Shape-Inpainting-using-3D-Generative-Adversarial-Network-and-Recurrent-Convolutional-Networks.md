---
layout: post
title: "Shape Inpainting using 3D Generative Adversarial Network and Recurrent Convolutional Networks"
date: 2017-11-17 02:01:11
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN CNN
author: Weiyue Wang, Qiangui Huang, Suya You, Chao Yang, Ulrich Neumann
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in convolutional neural networks have shown promising results in 3D shape completion. But due to GPU memory limitations, these methods can only produce low-resolution outputs. To inpaint 3D models with semantic plausibility and contextual details, we introduce a hybrid framework that combines a 3D Encoder-Decoder Generative Adversarial Network (3D-ED-GAN) and a Long-term Recurrent Convolutional Network (LRCN). The 3D-ED-GAN is a 3D convolutional neural network trained with a generative adversarial paradigm to fill missing 3D data in low-resolution. LRCN adopts a recurrent neural network architecture to minimize GPU memory usage and incorporates an Encoder-Decoder pair into a Long Short-term Memory Network. By handling the 3D model as a sequence of 2D slices, LRCN transforms a coarse 3D shape into a more complete and higher resolution volume. While 3D-ED-GAN captures global contextual structure of the 3D shape, LRCN localizes the fine-grained details. Experimental results on both real-world and synthetic data show reconstructions from corrupted models result in complete and high-resolution 3D objects.

##### Abstract (translated by Google)
卷积神经网络的最新进展已经在3D形状完成中显示出有希望的结果。但是由于GPU内存的限制，这些方法只能产生低分辨率的输出。为了修复具有语义可信性和上下文细节的3D模型，我们引入了结合3D编码器 - 解码器生成对抗网络（3D-ED-GAN）和长期递归卷积网络（LRCN）的混合框架。 3D-ED-GAN是一个三维卷积神经网络，用生成的对抗范例进行训练，以低分辨率填充缺失的3D数据。 LRCN采用递归神经网络架构来最大限度地减少GPU内存使用，并将编码器 - 解码器对合并到长期短期内存网络中。通过将3D模型作为一系列二维切片进行处理，LRCN将粗糙的三维形状转换为更完整，更高分辨率的体积。 3D-ED-GAN捕捉3D形状的全局上下文结构，而LRCN定位细粒度的细节。现实世界和合成数据的实验结果都表明，从腐蚀模型重构得到完整和高分辨率的三维物体。

##### URL
[https://arxiv.org/abs/1711.06375](https://arxiv.org/abs/1711.06375)

##### PDF
[https://arxiv.org/pdf/1711.06375](https://arxiv.org/pdf/1711.06375)

