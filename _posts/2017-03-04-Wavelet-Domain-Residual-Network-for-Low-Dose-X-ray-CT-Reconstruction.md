---
layout: post
title: "Wavelet Domain Residual Network for Low-Dose X-ray CT Reconstruction"
date: 2017-03-04 02:28:54
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Eunhee Kang, junhong Min, Jong Chul Ye
mathjax: true
---

* content
{:toc}

##### Abstract
Model based iterative reconstruction (MBIR) algorithms for low-dose X-ray CT are computationally complex because of the repeated use of the forward and backward projection. Inspired by this success of deep learning in computer vision applications, we recently proposed a deep convolutional neural network (CNN) for low-dose X-ray CT and won the second place in 2016 AAPM Low-Dose CT Grand Challenge. However, some of the texture are not fully recovered, which was unfamiliar to some radiologists. To cope with this problem, here we propose a direct residual learning approach on directional wavelet domain to solve this problem and to improve the performance against previous work. In particular, the new network estimates the noise of each input wavelet transform, and then the de-noised wavelet coefficients are obtained by subtracting the noise from the input wavelet transform bands. The experimental results confirm that the proposed network has significantly improved performance, preserving the detail texture of the original images.

##### Abstract (translated by Google)
由于重复使用正向和反向投影，基于模型的低剂量X射线CT的迭代重建（MBIR）算法计算复杂。受到计算机视觉应用深度学习的成功启发，我们最近提出了低剂量X射线CT的深度卷积神经网络（CNN），并在2016年AAPM低剂量CT大挑战赛中获得第二名。然而，一些纹理不完全恢复，这是一些放射科医生不熟悉。为了解决这个问题，在这里我们提出了一种直接的方向小波域残差学习方法来解决这个问题，并提高对以前的工作表现。特别地，新网络估计每个输入小波变换的噪声，然后通过从输入小波变换带中减去噪声来获得去噪小波系数。实验结果证实，所提出的网络具有显着改善的性能，保留了原始图像的细节结构。

##### URL
[https://arxiv.org/abs/1703.01383](https://arxiv.org/abs/1703.01383)

##### PDF
[https://arxiv.org/pdf/1703.01383](https://arxiv.org/pdf/1703.01383)

