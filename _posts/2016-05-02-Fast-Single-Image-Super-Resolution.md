---
layout: post
title: "Fast Single Image Super-Resolution"
date: 2016-05-02 13:40:30
categories: arXiv_CV
tags: arXiv_CV Regularization Super_Resolution Optimization
author: Ningning Zhao, Qi Wei, Adrian Basarab, Nicolas Dobigeon, Denis Kouame, Jean-Yves Tourneret
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of single image super-resolution (SR), which consists of recovering a high resolution image from its blurred, decimated and noisy version. The existing algorithms for single image SR use different strategies to handle the decimation and blurring operators. In addition to the traditional first-order gradient methods, recent techniques investigate splitting-based methods dividing the SR problem into up-sampling and deconvolution steps that can be easily solved. Instead of following this splitting strategy, we propose to deal with the decimation and blurring operators simultaneously by taking advantage of their particular properties in the frequency domain, leading to a new fast SR approach. Specifically, an analytical solution can be obtained and implemented efficiently for the Gaussian prior or any other regularization that can be formulated into an $\ell_2$-regularized quadratic model, i.e., an $\ell_2$-$\ell_2$ optimization problem. Furthermore, the flexibility of the proposed SR scheme is shown through the use of various priors/regularizations, ranging from generic image priors to learning-based approaches. In the case of non-Gaussian priors, we show how the analytical solution derived from the Gaussian case can be embedded intotraditional splitting frameworks, allowing the computation cost of existing algorithms to be decreased significantly. Simulation results conducted on several images with different priors illustrate the effectiveness of our fast SR approach compared with the existing techniques.

##### Abstract (translated by Google)
本文介绍了单幅图像超分辨率（SR）的问题，它包括从模糊，抽取和噪声版本中恢复高分辨率图像。现有的单幅图像SR算法采用不同的策略处理抽取和模糊操作。除了传统的一阶梯度方法之外，最近的技术还研究了基于分裂的方法，将SR问题划分为上采样和解卷积步骤，这些步骤可以很容易地解决。我们不是采用这种分裂策略，而是利用其在频域中的特性来同时处理抽取和模糊运算，从而导致一种新的快速SR方法。具体而言，可以为高斯先验或任何其他正则化可以有效地获得和实施解析解，其可以被表达为$ \ ell_2 $  - 调节的二次模型，即$ \ ell_2 $  -  $ \ ell_2 $优化问题。此外，所提出的SR方案的灵活性通过使用各种先验/正则化来示出，从通用图像先验到基于学习的方法。在非高斯先验的情况下，我们展示了如何从高斯情况导出的解析解可以嵌入到非传统的分裂框架中，从而使现有算法的计算成本大大降低。在不同先验的几幅图像上进行的仿真结果说明了与现有技术相比，我们的快速SR方法的有效性。

##### URL
[https://arxiv.org/abs/1510.00143](https://arxiv.org/abs/1510.00143)

##### PDF
[https://arxiv.org/pdf/1510.00143](https://arxiv.org/pdf/1510.00143)

