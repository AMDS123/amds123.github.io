---
layout: post
title: "C2MSNet: A Novel approach for single image haze removal"
date: 2018-01-25 14:16:14
categories: arXiv_CV
tags: arXiv_CV CNN
author: Akshay Dudhane, Subrahmanyam Murala
mathjax: true
---

* content
{:toc}

##### Abstract
Degradation of image quality due to the presence of haze is a very common phenomenon. Existing DehazeNet [3], MSCNN [11] tackled the drawbacks of hand crafted haze relevant features. However, these methods have the problem of color distortion in gloomy (poor illumination) environment. In this paper, a cardinal (red, green and blue) color fusion network for single image haze removal is proposed. In first stage, network fusses color information present in hazy images and generates multi-channel depth maps. The second stage estimates the scene transmission map from generated dark channels using multi channel multi scale convolutional neural network (McMs-CNN) to recover the original scene. To train the proposed network, we have used two standard datasets namely: ImageNet [5] and D-HAZY [1]. Performance evaluation of the proposed approach has been carried out using structural similarity index (SSIM), mean square error (MSE) and peak signal to noise ratio (PSNR). Performance analysis shows that the proposed approach outperforms the existing state-of-the-art methods for single image dehazing.

##### Abstract (translated by Google)
由于雾度的存在而使图像质量下降是非常普遍的现象。现有的DehazeNet [3]，MSCNN [11]解决了手工制造雾霾相关特征的缺点。但是，这些方法在阴暗（不良照明）的环境中存在颜色失真的问题。本文提出了一种红色，绿色和蓝色的单色图像去雾方法。在第一阶段，网络将朦胧图像中的颜色信息混合在一起，并生成多通道深度图。第二阶段使用多通道多尺度卷积神经网络（McMs-CNN）从生成的暗通道估计场景传输图以恢复原始场景。为了训练提出的网络，我们使用了两个标准数据集：ImageNet [5]和D-HAZY [1]。已经使用结构相似性指数（SSIM），均方误差（MSE）和峰值信噪比（PSNR）对所提出的方法进行了性能评估。性能分析表明，所提出的方法胜过现有的单一图像去雾方法。

##### URL
[http://arxiv.org/abs/1801.08406](http://arxiv.org/abs/1801.08406)

##### PDF
[http://arxiv.org/pdf/1801.08406](http://arxiv.org/pdf/1801.08406)

