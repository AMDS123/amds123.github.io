---
layout: post
title: "Foreground Segmentation Using a Triplet Convolutional Neural Network for Multiscale Feature Encoding"
date: 2018-01-07 18:33:43
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Detection
author: Long Ang Lim, Hacer Yalim Keles
mathjax: true
---

* content
{:toc}

##### Abstract
A common approach for moving objects segmentation in a scene is to perform a background subtraction. Several methods have been proposed in this domain. However, they lack the ability of handling various difficult scenarios such as illumination changes, background or camera motion, camouflage effect, shadow etc. To address these issues, we propose a robust and flexible encoder-decoder type neural network based approach. We adapt a pre-trained convolutional network, i.e. VGG-16 Net, under a triplet framework in the encoder part to embed an image in multiple scales into the feature space and use a transposed convolutional network in the decoder part to learn a mapping from feature space to image space. We train this network end-to-end by using only a few training samples. Our network takes an RGB image in three different scales and produces a foreground segmentation probability mask for the corresponding image. In order to evaluate our model, we entered the Change Detection 2014 Challenge (changedetection.net) and our method outperformed all the existing state-of-the-art methods by an average F-Measure of 0.9770. Our source code will be made publicly available at https://github.com/lim-anggun/FgSegNet.

##### Abstract (translated by Google)
在场景中移动对象分割的常用方法是执行背景减除。在这个领域已经提出了几种方法。针对这些问题，本文提出了一种鲁棒性强，灵活性强的编解码器型神经网络方法。在编码器部分的三重结构下，我们调整了一个预先训练的卷积网络，即VGG-16网络，将多尺度的图像嵌入到特征空间中，并且在解码器部分使用转置的卷积网络来学习从特征空间形象空间。我们只使用少量的训练样本来对这个网络进行端到端的训练。我们的网络以三种不同的比例尺拍摄RGB图像，并为相应的图像生成前景分割概率蒙版。为了评估我们的模型，我们进入了Change Detection 2014挑战（changedetection.net），我们的方法的平均F-Measure为0.9770，胜过了所有现有的最先进的方法。我们的源代码将在https://github.com/lim-anggun/FgSegNet公开。

##### URL
[http://arxiv.org/abs/1801.02225](http://arxiv.org/abs/1801.02225)

##### PDF
[http://arxiv.org/pdf/1801.02225](http://arxiv.org/pdf/1801.02225)

