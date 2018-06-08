---
layout: post
title: "Spatial Frequency Loss for Learning Convolutional Autoencoders"
date: 2018-06-06 08:34:12
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Naoyuki Ichimura
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a learning method for convolutional autoencoders (CAEs) for extracting features from images. CAEs can be obtained by utilizing convolutional neural networks to learn an approximation to the identity function in an unsupervised manner. The loss function based on the pixel loss (PL) that is the mean squared error between the pixel values of original and reconstructed images is the common choice for learning. However, using the loss function leads to blurred reconstructed images. A method for learning CAEs using a loss function computed from features reflecting spatial frequencies is proposed to mitigate the problem. The blurs in reconstructed images show lack of high spatial frequency components mainly constituting edges and detailed textures that are important features for tasks such as object detection and spatial matching. In order to evaluate the lack of components, a convolutional layer with a Laplacian filter bank as weights is added to CAEs and the mean squared error of features in a subband, called the spatial frequency loss (SFL), is computed from the outputs of each filter. The learning is performed using a loss function based on the SFL. Empirical evaluation demonstrates that using the SFL reduces the blurs in reconstructed images.

##### Abstract (translated by Google)
本文提出了一种卷积自动编码器（CAEs）的学习方法，用于从图像中提取特征。可以通过利用卷积神经网络以无监督的方式学习对身份函数的近似来获得CAE。基于像素损失（PL）的损失函数是原始图像和重构图像的像素值之间的均方差，是学习的常用选择。但是，使用损失函数会导致重建图像模糊。提出了一种使用从反映空间频率的特征计算的损失函数来学习CAE的方法来缓解该问题。重建图像中的模糊显示，缺乏主要构成边缘和高度空间频率分量的细节纹理，这些是物体检测和空间匹配等任务的重要特征。为了评估组件的不足，将具有拉普拉斯滤波器组作为权重的卷积层添加到CAE中，并且子频带中的特征的均方误差称为空间频率损失（SFL），从每个频带的输出计算过滤。使用基于SFL的损失函数来执行学习。经验评估表明，使用SFL可以减少重建图像中的模糊。

##### URL
[http://arxiv.org/abs/1806.02336](http://arxiv.org/abs/1806.02336)

##### PDF
[http://arxiv.org/pdf/1806.02336](http://arxiv.org/pdf/1806.02336)

