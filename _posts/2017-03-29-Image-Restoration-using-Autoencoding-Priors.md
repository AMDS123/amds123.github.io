---
layout: post
title: "Image Restoration using Autoencoding Priors"
date: 2017-03-29 10:51:49
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Gradient_Descent
author: Siavash Arjomand Bigdeli, Matthias Zwicker
mathjax: true
---

* content
{:toc}

##### Abstract
We propose to leverage denoising autoencoder networks as priors to address image restoration problems. We build on the key observation that the output of an optimal denoising autoencoder is a local mean of the true data density, and the autoencoder error (the difference between the output and input of the trained autoencoder) is a mean shift vector. We use the magnitude of this mean shift vector, that is, the distance to the local mean, as the negative log likelihood of our natural image prior. For image restoration, we maximize the likelihood using gradient descent by backpropagating the autoencoder error. A key advantage of our approach is that we do not need to train separate networks for different image restoration tasks, such as non-blind deconvolution with different kernels, or super-resolution at different magnification factors. We demonstrate state of the art results for non-blind deconvolution and super-resolution using the same autoencoding prior.

##### Abstract (translated by Google)
我们建议利用去噪自动编码器网络作为先验来解决图像恢复问题。我们建立在一个关键的观察结果上，即最优降噪自动编码器的输出是真实数据密度的局部均值，并且自编码器误差（训练自动编码器的输出和输入之间的差值）是平均移位矢量。我们使用这个均值平移向量的幅度，即到局部均值的距离，作为我们自然图像之前的负对数似然。对于图像恢复，我们通过反向传播自动编码器错误使用梯度下降来最大化可能性。我们的方法的一个关键优势是我们不需要为不同的图像恢复任务训练单独的网络，如不同的内核的非盲解卷积，或在不同的放大因子下的超分辨率。我们展示了先前使用相同自动编码的非盲解卷积和超分辨率的最先进结果。

##### URL
[https://arxiv.org/abs/1703.09964](https://arxiv.org/abs/1703.09964)

##### PDF
[https://arxiv.org/pdf/1703.09964](https://arxiv.org/pdf/1703.09964)

