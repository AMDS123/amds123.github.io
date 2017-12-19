---
layout: post
title: "Conjugate Gradient Acceleration of Non-Linear Smoothing Filters"
date: 2015-09-04 16:06:38
categories: arXiv_CV
tags: arXiv_CV
author: Andrew Knyazev, Alexander Malyshev
mathjax: true
---

* content
{:toc}

##### Abstract
The most efficient signal edge-preserving smoothing filters, e.g., for denoising, are non-linear. Thus, their acceleration is challenging and is often performed in practice by tuning filter parameters, such as by increasing the width of the local smoothing neighborhood, resulting in more aggressive smoothing of a single sweep at the cost of increased edge blurring. We propose an alternative technology, accelerating the original filters without tuning, by running them through a special conjugate gradient method, not affecting their quality. The filter non-linearity is dealt with by careful freezing and restarting. Our initial numerical experiments on toy one-dimensional signals demonstrate 20x acceleration of the classical bilateral filter and 3-5x acceleration of the recently developed guided filter.

##### Abstract (translated by Google)
例如用于去噪的最有效的信号边缘保留平滑滤波器是非线性的。因此，它们的加速是具有挑战性的，并且通常在实践中通过调整滤波器参数（例如通过增加局部平滑邻域的宽度）来执行，导致以增加的边缘模糊为代价的更加主动的单次扫描平滑。我们提出了一种替代技术，通过使用特殊的共轭梯度方法来加速原始滤波器而不进行调谐，而不影响其质量。通过小心的冻结和重新启动来处理滤波器的非线性。我们对玩具一维信号的初始数值实验证明了经典双边滤波器的20倍加速度和最近开发的导向滤波器的3-5倍加速度。

##### URL
[https://arxiv.org/abs/1509.01514](https://arxiv.org/abs/1509.01514)

##### PDF
[https://arxiv.org/pdf/1509.01514](https://arxiv.org/pdf/1509.01514)

