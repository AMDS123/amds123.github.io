---
layout: post
title: "A MAP-MRF filter for phase-sensitive coil combination in autocalibrating partially parallel susceptibility weighted MRI"
date: 2016-10-29 12:38:41
categories: arXiv_CV
tags: arXiv_CV
author: Sreekanth Madhusoodhanan, Joseph Suresh Paul
mathjax: true
---

* content
{:toc}

##### Abstract
A statistical approach for combination of channel phases is developed for optimizing the Contrast-to-Noise Ratio (CNR) in Susceptibility Weighted Images (SWI) acquired using autocalibrating partially parallel techniques. The unwrapped phase images of each coil are filtered using local random field based probabilistic weights, derived using energy functions representative of noisy sensitivity and tissue information pertaining to venous structure in the individual channel phase images. The channel energy functions are obtained as functions of local image intensities, first or second order clique phase difference and a threshold scaling parameter dependent on the input noise level. Whereas the expectation of the individual energy functions with respect to the noise distribution in clique phase differences is to be maximized for optimal filtering, the expectation of tissue energy function decreases and noise energy function increases with increase in threshold scale parameter. The optimum scaling parameter is shown to occur at the point where expectations of both energy functions contribute to the largest possible extent. It is shown that implementation of the filter in the same lines as that of Iterated Conditional Modes (ICM) algorithm provides structural enhancement in the coil combined phase, with reduced noise amplification. Application to simulated and in vivo multi-channel SWI shows that CNR of combined phase obtained using MAP-MRF filter is higher as compared to that of coil combination using weighted average.

##### Abstract (translated by Google)
为了优化使用自动校准部分平行技术获得的敏感性加权图像（SWI）中的对比噪声比（CNR），开发了用于信道相位组合的统计方法。使用基于局部随机场的概率权重对每个线圈的展开的相位图像进行滤波，使用代表噪声灵敏度的能量函数以及与单个通道相位图像中的静脉结构有关的组织信息来导出。信道能量函数是作为局部图像强度，一阶或二阶团体相位差和取决于输入噪声电平的阈值缩放参数的函数而获得的。而个别能量函数相对于团体相位差中噪声分布的期望最大化以实现最佳滤波，组织能量函数的期望值降低，噪声能量函数随着阈值尺度参数的增加而增加。显示最佳缩放参数发生在两个能量函数的期望贡献最大可能程度的点处。结果表明，与迭代条件模式（ICM）算法相同的滤波器实现了线圈组合相位的结构增强，降低了噪声放大。应用到模拟和体内多通道SWI显示使用MAP-MRF过滤器获得的组合相的CNR比使用加权平均的线圈组合的CNR更高。

##### URL
[https://arxiv.org/abs/1610.09498](https://arxiv.org/abs/1610.09498)

##### PDF
[https://arxiv.org/pdf/1610.09498](https://arxiv.org/pdf/1610.09498)

