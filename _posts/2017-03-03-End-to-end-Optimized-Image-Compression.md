---
layout: post
title: "End-to-end Optimized Image Compression"
date: 2017-03-03 14:53:13
categories: arXiv_CV
tags: arXiv_CV CNN Gradient_Descent
author: Johannes Ballé, Valero Laparra, Eero P. Simoncelli
mathjax: true
---

* content
{:toc}

##### Abstract
We describe an image compression method, consisting of a nonlinear analysis transformation, a uniform quantizer, and a nonlinear synthesis transformation. The transforms are constructed in three successive stages of convolutional linear filters and nonlinear activation functions. Unlike most convolutional neural networks, the joint nonlinearity is chosen to implement a form of local gain control, inspired by those used to model biological neurons. Using a variant of stochastic gradient descent, we jointly optimize the entire model for rate-distortion performance over a database of training images, introducing a continuous proxy for the discontinuous loss function arising from the quantizer. Under certain conditions, the relaxed loss function may be interpreted as the log likelihood of a generative model, as implemented by a variational autoencoder. Unlike these models, however, the compression model must operate at any given point along the rate-distortion curve, as specified by a trade-off parameter. Across an independent set of test images, we find that the optimized method generally exhibits better rate-distortion performance than the standard JPEG and JPEG 2000 compression methods. More importantly, we observe a dramatic improvement in visual quality for all images at all bit rates, which is supported by objective quality estimates using MS-SSIM.

##### Abstract (translated by Google)
我们描述了一种图像压缩方法，包括非线性分析变换，均匀量化器和非线性综合变换。这些变换是在卷积线性滤波器和非线性激活函数的三个连续阶段构建的。与大多数卷积神经网络不同，选择联合非线性来实现局部增益控制的一种形式，其灵感来自用于模拟生物神经元的那些。使用随机梯度下降的变体，我们联合优化整个训练图像数据库的速率失真性能模型，引入量化器产生的不连续损失函数的连续代表。在某些情况下，放松损失函数可能被解释为一个生成模型的对数似然性，如由一个变分自动编码器实现的。但是，与这些模型不同的是，压缩模型必须沿着速率 - 失真曲线的任何给定点运行，这由折衷参数指定。在一组独立的测试图像上，我们发现优化的方法通常比标准的JPEG和JPEG 2000压缩方法具有更好的速率失真性能。更重要的是，我们观察到所有比特率下的所有图像的视觉质量有显着提高，这通过使用MS-SSIM的客观质量估计得到支持。

##### URL
[https://arxiv.org/abs/1611.01704](https://arxiv.org/abs/1611.01704)

##### PDF
[https://arxiv.org/pdf/1611.01704](https://arxiv.org/pdf/1611.01704)

