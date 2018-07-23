---
layout: post
title: "Fully Convolutional Pixel Adaptive Image Denoiser"
date: 2018-07-19 14:34:11
categories: arXiv_CV
tags: arXiv_CV CNN
author: Sungmin Cha, Taesup Moon
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new denoising algorithm, dubbed as Fully Convolutional Adaptive Image DEnoiser (FC-AIDE), that can learn from offline supervised training set with a fully convolutional neural network architecture as well as adaptively fine-tune the denoiser for each given noisy image. We mainly follow the framework of the recently proposed Neural AIDE, which formulates the denoiser to be context-based pixelwise affine mappings and utilizes the unbiased estimator of MSE of such denoisers. The three main contributions we make to significantly improve upon the original Neural AIDE are the followings; 1) implementing a novel fully convolutional architecture that boosts the base supervised model, 2) introducing data augmentation for adaptive fine-tuning to achieve much stronger adaptivity, and 3) proposing an effective unknown noise level estimation method. As a result, FC-AIDE is shown to significantly outperform the state-of-the-art CNN-based denoisers on two standard benchmark dataset as well as on a much challenging blind denoising dataset, in which nothing is known about the noise level, noise distribution, or image characteristics.

##### Abstract (translated by Google)
我们提出了一种新的去噪算法，称为完全卷积自适应图像去噪器（FC-AIDE），它可以从具有完全卷积神经网络结构的离线监督训练集中学习，并自适应地微调每个给定噪声图像的去噪器。我们主要遵循最近提出的神经AIDE的框架，该神经AIDE将降噪器表示为基于上下文的像素仿射映射，并利用这种降噪器的MSE的无偏估计。我们为显着改善原始神经AIDE所做的三个主要贡献如下： 1）实现一种新的完全卷积结构，增强基础监督模型，2）引入自适应微调的数据增强以实现更强的自适应性，以及3）提出有效的未知噪声水平估计方法。因此，FC-AIDE在两个标准基准数据集以及一个非常具有挑战性的盲目去噪数据集上显示出明显优于最先进的基于CNN的降噪器，其中对噪声水平一无所知，噪声分布或图像特征。

##### URL
[http://arxiv.org/abs/1807.07569](http://arxiv.org/abs/1807.07569)

##### PDF
[http://arxiv.org/pdf/1807.07569](http://arxiv.org/pdf/1807.07569)

