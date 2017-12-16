---
layout: post
title: "Automatic Brain Tumor Segmentation using Cascaded Anisotropic Convolutional Neural Networks"
date: 2017-09-01 16:11:34
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Prediction
author: Guotai Wang, Wenqi Li, Sebastien Ourselin, Tom Vercauteren
mathjax: true
---

* content
{:toc}

##### Abstract
A cascade of fully convolutional neural networks is proposed to segment multi-modality MR images with brain tumor into background and three subregions: enhanced tumor core, whole tumor and tumor core. The cascade is designed to decompose the multi-class segmentation into a sequence of three binary segmentations according to the subregion hierarchy. Segmentation of the first (second) step is used as a crisp binary mask for the second (third) step. Each network consists of multiple layers of anisotropic and dilated convolution filters that were obtained by training each network end-to-end. Residual connections and multi-scale predictions were employed in these networks to boost the segmentation performance. Experiments with BraTS 2017 validation set shows the proposed method achieved average Dice scores of 0.7859, 0.9050, 0.8378 for enhanced tumor core, whole tumor and tumor core respectively.

##### Abstract (translated by Google)
提出了一种完全卷积神经网络级联方法，将脑肿瘤多模态MR图像分为背景和三个子区域：增强型肿瘤核心，全肿瘤和肿瘤核心。级联被设计成根据子区域层级将多级分割分解成三个二进制分割的序列。第一步（第二步）的分割用作第二步（第三步）的清晰二进制掩码。每个网络由多层各向异性和膨胀卷积滤波器组成，这些滤波器是通过端到端训练每个网络而获得的。在这些网络中采用了残余连接和多尺度预测来提高分割性能。用BraTS2017验证集进行的实验显示，所提出的方法分别对于增强的肿瘤核心，全肿瘤和肿瘤核心实现了0.7859,0.9050,0.8378的平均Dice分数。

##### URL
[https://arxiv.org/abs/1709.00382](https://arxiv.org/abs/1709.00382)

##### PDF
[https://arxiv.org/pdf/1709.00382](https://arxiv.org/pdf/1709.00382)

