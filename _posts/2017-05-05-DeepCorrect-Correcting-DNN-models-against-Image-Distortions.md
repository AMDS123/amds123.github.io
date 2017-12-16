---
layout: post
title: "DeepCorrect: Correcting DNN models against Image Distortions"
date: 2017-05-05 21:52:49
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Recognition
author: Tejas Borkar, Lina Karam
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, the widespread use of deep neural networks (DNNs) has facilitated great improvements in performance for computer vision tasks like image classification and object recognition. In most realistic computer vision applications, an input image undergoes some form of image distortion such as blur and additive noise during image acquisition or transmission. Deep networks trained on pristine images perform poorly when tested on distorted images affected by image blur or additive noise. In this paper, we evaluate the effect of image distortions like Gaussian blur and additive noise on the outputs of pre-trained convolutional filters. We propose a metric to identify the most noise susceptible convolutional filters and rank them in order of the highest gain in classification accuracy upon correction. In our proposed approach called DeepCorrect, we apply small convolutional filter blocks on top of these ranked filters and train them to correct the worst noise and blur affected filter outputs. Applying DeepCorrect on the CIFAR-100 dataset, we significantly improve the robustness of DNNs against distorted images and also outperform the alternative approach of fine-tuning networks.

##### Abstract (translated by Google)
近年来，深度神经网络（DNN）的广泛使用促进了诸如图像分类和目标识别之类的计算机视觉任务的性能的极大改进。在大多数现实的计算机视觉应用中，输入图像在图像采集或传输期间经历某种形式的图像失真，例如模糊和加性噪声。对原始图像进行训练的深度网络在受图像模糊或加性噪声影响的失真图像上进行测试时性能较差。在本文中，我们评估像高斯模糊和加性噪声的图像失真对预先训练的卷积滤波器的输出的影响。我们提出了一个度量标准，以确定最易受噪声影响的卷积滤波器，并按照修正后分类精度的最高增益排序。在我们提出的称为DeepCorrect的方法中，我们将小卷积滤波器块应用到这些排序的滤波器的顶部，并对它们进行训练以纠正最差的噪声和模糊影响的滤波器输出。在CIFAR-100数据集上应用DeepCorrect，我们显着提高了DNN对于失真图像的鲁棒性，同时也超越了微调网络的替代方法。

##### URL
[https://arxiv.org/abs/1705.02406](https://arxiv.org/abs/1705.02406)

##### PDF
[https://arxiv.org/pdf/1705.02406](https://arxiv.org/pdf/1705.02406)

