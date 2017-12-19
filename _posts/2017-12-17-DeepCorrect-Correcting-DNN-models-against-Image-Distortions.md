---
layout: post
title: "DeepCorrect: Correcting DNN models against Image Distortions"
date: 2017-12-17 06:56:39
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Recognition
author: Tejas Borkar, Lina Karam
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, the widespread use of deep neural networks (DNNs) has facilitated great improvements in performance for computer vision tasks like image classification and object recognition. In most realistic computer vision applications, an input image undergoes some form of image distortion such as blur and additive noise during image acquisition or transmission. Deep networks trained on pristine images perform poorly when tested on such distortions. In this paper, we evaluate the effect of image distortions like Gaussian blur and additive noise on the activations of pre-trained convolutional filters. We propose a metric to identify the most noise susceptible convolutional filters and rank them in order of the highest gain in classification accuracy upon correction. In our proposed approach called DeepCorrect, we apply small stacks of convolutional layers with residual connections, at the output of these ranked filters and train them to correct the worst distortion affected filter activations, whilst leaving the rest of the pre-trained filter outputs in the network unchanged. Performance results show that applying DeepCorrect models for common vision tasks like image classification (CIFAR-100, ImageNet), object recognition (Caltech-101, Caltech-256) and scene classification (SUN-397), significantly improves the robustness of DNNs against distorted images and outperforms the alternative approach of network fine-tuning.

##### Abstract (translated by Google)
近年来，深度神经网络（DNN）的广泛使用促进了诸如图像分类和目标识别之类的计算机视觉任务的性能的极大改进。在大多数现实的计算机视觉应用中，输入图像在图像采集或传输期间经历某种形式的图像失真，例如模糊和加性噪声。在原始图像上进行训练的深度网络在进行这种失真测试时表现不佳。在本文中，我们评估像高斯模糊和加性噪声的图像失真对预先训练的卷积滤波器的激活的影响。我们提出了一个度量标准，以确定最易受噪声影响的卷积滤波器，并按照修正后分类精度的最高增益排序。在我们提出的称为DeepCorrect的方法中，我们在这些分级滤波器的输出端应用具有剩余连接的卷积层的小叠层，并对它们进行训练，以校正最坏的失真影响的滤波器激活，同时将剩余的预先训练的滤波器输出网络不变。性能结果表明，将DeepCorrect模型应用于图像分类（CIFAR-100，ImageNet），物体识别（Caltech-101，Caltech-256）和场景分类（SUN-397）等常见视觉任务中，显着提高了DNN对畸变的鲁棒性图像，并且胜过网络微调的替代方法。

##### URL
[http://arxiv.org/abs/1705.02406](http://arxiv.org/abs/1705.02406)

##### PDF
[http://arxiv.org/pdf/1705.02406](http://arxiv.org/pdf/1705.02406)

