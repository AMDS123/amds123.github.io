---
layout: post
title: "Generating High-Quality Crowd Density Maps using Contextual Pyramid CNNs"
date: 2017-08-02 22:54:21
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN Classification
author: Vishwanath A. Sindagi, Vishal M. Patel
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel method called Contextual Pyramid CNN (CP-CNN) for generating high-quality crowd density and count estimation by explicitly incorporating global and local contextual information of crowd images. The proposed CP-CNN consists of four modules: Global Context Estimator (GCE), Local Context Estimator (LCE), Density Map Estimator (DME) and a Fusion-CNN (F-CNN). GCE is a VGG-16 based CNN that encodes global context and it is trained to classify input images into different density classes, whereas LCE is another CNN that encodes local context information and it is trained to perform patch-wise classification of input images into different density classes. DME is a multi-column architecture-based CNN that aims to generate high-dimensional feature maps from the input image which are fused with the contextual information estimated by GCE and LCE using F-CNN. To generate high resolution and high-quality density maps, F-CNN uses a set of convolutional and fractionally-strided convolutional layers and it is trained along with the DME in an end-to-end fashion using a combination of adversarial loss and pixel-level Euclidean loss. Extensive experiments on highly challenging datasets show that the proposed method achieves significant improvements over the state-of-the-art methods.

##### Abstract (translated by Google)
我们提出了一种称为上下文金字塔CNN（CP-CNN）的新方法，通过明确地结合人群图像的全局和局部上下文信息来生成高质量人群密度和计数估计。提出的CP-CNN由全局上下文估计器（GCE），局部上下文估计器（LCE），密度映射估计器（DME）和融合CNN（F-CNN）四个模块组成。 GCE是一个基于VGG-16的CNN，它编码全局上下文，并将输入图像分类为不同的密度类别，而LCE是另一种CNN，用于编码本地上下文信息，并且训练将输入图像的补丁方式分类为不同的密度等级。 DME是一种基于多列体系结构的CNN，旨在从输入图像中生成高维特征映射，与GCE和LCE使用F-CNN估计的上下文信息进行融合。为了产生高分辨率和高质量的密度图，F-CNN使用一组卷积和分步卷积层，并且与DME一起以端对端的方式训练，使用对抗损失和像素 - 欧几里得损失。在高度具有挑战性的数据集上的大量实验表明，所提出的方法比现有技术的方法实现了显着的改进。

##### URL
[https://arxiv.org/abs/1708.00953](https://arxiv.org/abs/1708.00953)

##### PDF
[https://arxiv.org/pdf/1708.00953](https://arxiv.org/pdf/1708.00953)

