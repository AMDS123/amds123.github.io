---
layout: post
title: "Image Dehazing using Bilinear Composition Loss Function"
date: 2017-10-01 02:39:11
categories: arXiv_CV
tags: arXiv_CV CNN Relation
author: Hui Yang, Jinshan Pan, Qiong Yan, Wenxiu Sun, Jimmy Ren, Yu-Wing Tai
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce a bilinear composition loss function to address the problem of image dehazing. Previous methods in image dehazing use a two-stage approach which first estimate the transmission map followed by clear image estimation. The drawback of a two-stage method is that it tends to boost local image artifacts such as noise, aliasing and blocking. This is especially the case for heavy haze images captured with a low quality device. Our method is based on convolutional neural networks. Unique in our method is the bilinear composition loss function which directly model the correlations between transmission map, clear image, and atmospheric light. This allows errors to be back-propagated to each sub-network concurrently, while maintaining the composition constraint to avoid overfitting of each sub-network. We evaluate the effectiveness of our proposed method using both synthetic and real world examples. Extensive experiments show that our method outperfoms state-of-the-art methods especially for haze images with severe noise level and compressions.

##### Abstract (translated by Google)
在本文中，我们引入双线性成分损失函数来解决图像去雾的问题。先前的图像除雾方法使用两阶段方法，首先估计透射图，然后进行清晰的图像估计。两阶段方法的缺点是它倾向于增加局部图像伪像，如噪声，混叠和阻塞。对于使用低质量设备拍摄的重雾霾图像尤其如此。我们的方法是基于卷积神经网络。在我们的方法中独特的是双线性成分损失函数，它直接模拟透射图，清晰图像和大气光之间的相关性。这允许错误同时被反向传播到每个子网络，同时保持合成约束以避免每个子网络的过度拟合。我们使用合成和现实世界的例子来评估我们提出的方法的有效性。大量的实验表明，我们的方法超越了最先进的方法，特别是对于噪声水平和压缩严重的雾影像。

##### URL
[https://arxiv.org/abs/1710.00279](https://arxiv.org/abs/1710.00279)

##### PDF
[https://arxiv.org/pdf/1710.00279](https://arxiv.org/pdf/1710.00279)

