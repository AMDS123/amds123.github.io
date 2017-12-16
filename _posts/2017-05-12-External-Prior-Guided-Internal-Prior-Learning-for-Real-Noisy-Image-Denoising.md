---
layout: post
title: "External Prior Guided Internal Prior Learning for Real Noisy Image Denoising"
date: 2017-05-12 10:49:33
categories: arXiv_CV
tags: arXiv_CV
author: Jun Xu, Lei Zhang, David Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Most of existing image denoising methods learn image priors from either external data or the noisy image itself to remove noise. However, priors learned from external data may not be adaptive to the image to be denoised, while priors learned from the given noisy image may not be accurate due to the interference of corrupted noise. Meanwhile, the noise in real-world noisy images is very complex, which is hard to be described by simple distributions such as Gaussian distribution, making real noisy image denoising a very challenging problem. We propose to exploit the information in both external data and the given noisy image, and develop an external prior guided internal prior learning method for real noisy image denoising. We first learn external priors from an independent set of clean natural images. With the aid of learned external priors, we then learn internal priors from the given noisy image to refine the prior model. The external and internal priors are formulated as a set of orthogonal dictionaries to efficiently reconstruct the desired image. Extensive experiments are performed on several real noisy image datasets. The proposed method demonstrates highly competitive denoising performance, outperforming state-of-the-art denoising methods including those designed for real noisy images.

##### Abstract (translated by Google)
现有的大多数图像去噪方法都是通过外部数据或噪声图像本身来学习图像的先验信息，以去除噪声。然而，从外部数据学习的先验可能不适合于要去噪的图像，而从给定噪声图像学习的先验可能由于受到干扰的噪声干扰而不准确。同时，真实世界噪声图像中的噪声非常复杂，很难用高斯分布等简单分布来描述，使得真实噪声图像去噪成为一个非常具有挑战性的问题。我们建议利用外部数据和给定的噪声图像的信息，并开发一个外部事先引导的内部先验学习方法，用于真正的噪声图像去噪。我们首先从独立的干净的自然图像学习外部的先验。借助于学习的外部先验，我们从给定的噪声图像中学习内部先验，以改进先前的模型。外部和内部先验制定为一套正交的字典，以有效地重建所需的图像。对几个真实的噪声图像数据集进行了大量的实验。所提出的方法表现出高度竞争性的去噪性能，超越了最先进的去噪方法，包括那些为真实的噪声图像而设计的去噪方法。

##### URL
[https://arxiv.org/abs/1705.04505](https://arxiv.org/abs/1705.04505)

##### PDF
[https://arxiv.org/pdf/1705.04505](https://arxiv.org/pdf/1705.04505)

