---
layout: post
title: "Data Driven Robust Image Guided Depth Map Restoration"
date: 2015-12-26 12:04:54
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Wei Liu, Yun Gu, Chunhua Shen, Xiaogang Chen, Qiang Wu, Jie Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Depth maps captured by modern depth cameras such as Kinect and Time-of-Flight (ToF) are usually contaminated by missing data, noises and suffer from being of low resolution. In this paper, we present a robust method for high-quality restoration of a degraded depth map with the guidance of the corresponding color image. We solve the problem in an energy optimization framework that consists of a novel robust data term and smoothness term. To accommodate not only the noise but also the inconsistency between depth discontinuities and the color edges, we model both the data term and smoothness term with a robust exponential error norm function. We propose to use Iteratively Re-weighted Least Squares (IRLS) methods for efficiently solving the resulting highly non-convex optimization problem. More importantly, we further develop a data-driven adaptive parameter selection scheme to properly determine the parameter in the model. We show that the proposed approach can preserve fine details and sharp depth discontinuities even for a large upsampling factor ($8\times$ for example). Experimental results on both simulated and real datasets demonstrate that the proposed method outperforms recent state-of-the-art methods in coping with the heavy noise, preserving sharp depth discontinuities and suppressing the texture copy artifacts.

##### Abstract (translated by Google)
现代深度相机（如Kinect和飞行时间（ToF））捕获的深度图通常受到缺失数据，噪声和低分辨率的困扰。在本文中，我们提出了一个稳健的方法高品质的退化深度图恢复与相应的彩色图像的指导下。我们在一个能量优化框架中解决了这个问题，该框架由一个新颖的强大数据项和平滑项组成。为了适应不仅噪声，而且深度不连续性和颜色边缘之间的不一致性，我们用一个鲁棒的指数误差范数函数来模拟数据项和平滑项。我们建议使用迭代重新加权最小二乘（IRLS）方法来有效地解决由此产生的高度非凸优化问题。更重要的是，我们进一步开发了一个数据驱动的自适应参数选择方案，以正确确定模型中的参数。我们表明，即使对于一个大的上采样因子（例如$ 8 \ times $），所提出的方法可以保留精细的细节和尖锐的深度不连续性。在模拟数据集和真实数据集上的实验结果都表明，所提出的方法在应对严重的噪声，保留尖锐的深度不连续性和抑制纹理复制伪影方面胜过了最近的最先进的方法。

##### URL
[https://arxiv.org/abs/1512.08103](https://arxiv.org/abs/1512.08103)

##### PDF
[https://arxiv.org/pdf/1512.08103](https://arxiv.org/pdf/1512.08103)

