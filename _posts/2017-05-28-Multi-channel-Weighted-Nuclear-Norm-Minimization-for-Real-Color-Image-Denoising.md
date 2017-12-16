---
layout: post
title: "Multi-channel Weighted Nuclear Norm Minimization for Real Color Image Denoising"
date: 2017-05-28 08:51:39
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Jun Xu, Lei Zhang, David Zhang, Xiangchu Feng
mathjax: true
---

* content
{:toc}

##### Abstract
Most of the existing denoising algorithms are developed for grayscale images, while it is not a trivial work to extend them for color image denoising because the noise statistics in R, G, B channels can be very different for real noisy images. In this paper, we propose a multi-channel (MC) optimization model for real color image denoising under the weighted nuclear norm minimization (WNNM) framework. We concatenate the RGB patches to make use of the channel redundancy, and introduce a weight matrix to balance the data fidelity of the three channels in consideration of their different noise statistics. The proposed MC-WNNM model does not have an analytical solution. We reformulate it into a linear equality-constrained problem and solve it with the alternating direction method of multipliers. Each alternative updating step has closed-form solution and the convergence can be guaranteed. Extensive experiments on both synthetic and real noisy image datasets demonstrate the superiority of the proposed MC-WNNM over state-of-the-art denoising methods.

##### Abstract (translated by Google)
目前大多数的去噪算法都是针对灰度图像而开发的，而将彩色图像去噪的扩展方法并不是一件微不足道的工作，因为R，G，B通道中的噪声统计对于真实的噪声图像可能是非常不同的。在本文中，我们提出了一个在加权核范数最小化（WNNM）框架下的实时彩色图像去噪的多通道（MC）优化模型。我们连接RGB补丁以利用信道冗余度，并考虑到不同的噪声统计量，引入权重矩阵来平衡三个信道的数据保真度。所提出的MC-WNNM模型没有解析解。我们把它改写成一个线性的等式约束问题，并用乘数的交替方向法来求解。每个替代更新步骤都有封闭的解决方案，并且可以保证收敛。对合成和真实噪声图像数据集的大量实验证明了所提出的MC-WNNM优于现有技术的去噪方法的优越性。

##### URL
[https://arxiv.org/abs/1705.09912](https://arxiv.org/abs/1705.09912)

##### PDF
[https://arxiv.org/pdf/1705.09912](https://arxiv.org/pdf/1705.09912)

