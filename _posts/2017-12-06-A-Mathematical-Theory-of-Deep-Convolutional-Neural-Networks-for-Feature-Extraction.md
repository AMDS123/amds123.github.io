---
layout: post
title: 'A Mathematical Theory of Deep Convolutional Neural Networks for Feature Extraction'
date: 2017-12-06 08:55:50
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption CNN
author: Thomas Wiatowski, Helmut Bölcskei
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks have led to breakthrough results in numerous practical machine learning tasks such as classification of images in the ImageNet data set, control-policy-learning to play Atari games or the board game Go, and image captioning. Many of these applications first perform feature extraction and then feed the results thereof into a trainable classifier. The mathematical analysis of deep convolutional neural networks for feature extraction was initiated by Mallat, 2012. Specifically, Mallat considered so-called scattering networks based on a wavelet transform followed by the modulus non-linearity in each network layer, and proved translation invariance (asymptotically in the wavelet scale parameter) and deformation stability of the corresponding feature extractor. This paper complements Mallat's results by developing a theory that encompasses general convolutional transforms, or in more technical parlance, general semi-discrete frames (including Weyl-Heisenberg filters, curvelets, shearlets, ridgelets, wavelets, and learned filters), general Lipschitz-continuous non-linearities (e.g., rectified linear units, shifted logistic sigmoids, hyperbolic tangents, and modulus functions), and general Lipschitz-continuous pooling operators emulating, e.g., sub-sampling and averaging. In addition, all of these elements can be different in different network layers. For the resulting feature extractor we prove a translation invariance result of vertical nature in the sense of the features becoming progressively more translation-invariant with increasing network depth, and we establish deformation sensitivity bounds that apply to signal classes such as, e.g., band-limited functions, cartoon functions, and Lipschitz functions.

##### Abstract (translated by Google)
深卷积神经网络已经在许多实际的机器学习任务中取得了突破性的成果，例如ImageNet数据集中的图像分类，玩Atari游戏或棋盘游戏Go的控制政策学习以及图像字幕。这些应用程序中的许多首先执行特征提取，然后将其结果馈送到可训练的分类器中。特征提取的深度卷积神经网络的数学分析由Mallat于2012年发起。具体而言，Mallat考虑了所谓的基于小波变换的散射网络，然后在每个网络层中模数非线性，并证明了平移不变性（渐近在小波尺度参数）和相应的特征提取器的变形稳定性。本文通过开发一个包含一般卷积变换的理论来补充Mallat的结果，或者用更多的技术术语来说，一般的半离散帧（包括Weyl-Heisenberg滤波器，Curvelet，剪切波，Ridgelet，小波和学习滤波器），Lipschitz-连续非线性（例如，整形的线性单位，移位的逻辑斯蒂格双曲线，双曲线切线和模量函数）以及模拟（例如，二次采样和平均）的一般Lipschitz连续池操作。另外，所有这些元素在不同的网络层中可以是不同的。对于所得到的特征提取器，我们证明了随着网络深度逐渐变得越来越平移的特征意义上的垂直性质的平移不变性结果，并且我们建立了适用于信号类别的变形灵敏度边界，例如带限功能，卡通功能和Lipschitz功能。

##### URL
[https://arxiv.org/abs/1512.06293](https://arxiv.org/abs/1512.06293)

