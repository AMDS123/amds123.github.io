---
layout: post
title: "Interactive Medical Image Segmentation using Deep Learning with Image-specific Fine-tuning"
date: 2017-10-11 12:57:52
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN CNN Deep_Learning
author: Guotai Wang, Wenqi Li, Maria A. Zuluaga, Rosalind Pratt, Premal A. Patel, Michael Aertsen, Tom Doel, Anna L. David, Jan Deprest, Sebastien Ourselin, Tom Vercauteren
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) have achieved state-of-the-art performance for automatic medical image segmentation. However, they have not demonstrated sufficiently accurate and robust results for clinical use. In addition, they are limited by the lack of image-specific adaptation and the lack of generalizability to previously unseen object classes. To address these problems, we propose a novel deep learning-based framework for interactive segmentation by incorporating CNNs into a bounding box and scribble-based segmentation pipeline. We propose image-specific fine-tuning to make a CNN model adaptive to a specific test image, which can be either unsupervised (without additional user interactions) or supervised (with additional scribbles). We also propose a weighted loss function considering network and interaction-based uncertainty for the fine-tuning. We applied this framework to two applications: 2D segmentation of multiple organs from fetal MR slices, where only two types of these organs were annotated for training; and 3D segmentation of brain tumor core (excluding edema) and whole brain tumor (including edema) from different MR sequences, where only tumor cores in one MR sequence were annotated for training. Experimental results show that 1) our model is more robust to segment previously unseen objects than state-of-the-art CNNs; 2) image-specific fine-tuning with the proposed weighted loss function significantly improves segmentation accuracy; and 3) our method leads to accurate results with fewer user interactions and less user time than traditional interactive segmentation methods.

##### Abstract (translated by Google)
卷积神经网络（CNN）已经实现了自动医学图像分割的最新性能。然而，他们还没有证明足够的准确和强大的临床使用的结果。另外，由于缺乏图像特定的适应性以及缺乏对以前看不见的对象类的普遍性，它们受到限制。为了解决这些问题，我们提出了一种新的基于深度学习的交互式分割框架，将CNN纳入边界框和基于涂鸦的分割流水线。我们提出图像特定的微调，以使CNN模型适应于特定的测试图像，其可以是无监督的（没有额外的用户交互）或监督的（具有额外的涂鸦）。我们还提出了一个考虑网络和基于交互作用的微调不确定性的加权损失函数。我们将这个框架应用于两个应用：从胎儿MR切片的多个器官的2D分割，其中只有两种类型的这些器官被注释用于训练;以及不同MR序列的脑肿瘤核心（不包括水肿）和全脑肿瘤（包括水肿）的3D分割，其中仅一个MR序列的肿瘤核心被注释用于训练。实验结果表明：1）我们的模型比先进的CNN更有效地分割先前看不见的对象; 2）利用所提出的加权损失函数进行图像特定的微调显着提高了分割精度; 3）我们的方法比传统的交互式分割方法导致准确的结果，用户交互更少，用户时间更少。

##### URL
[https://arxiv.org/abs/1710.04043](https://arxiv.org/abs/1710.04043)

##### PDF
[https://arxiv.org/pdf/1710.04043](https://arxiv.org/pdf/1710.04043)

