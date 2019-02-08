---
layout: post
title: "DoPAMINE: Double-sided Masked CNN for Pixel Adaptive Multiplicative Noise Despeckling"
date: 2019-02-07 09:08:18
categories: arXiv_CV
tags: arXiv_CV
author: Sunghwan Joo, Sungmin Cha, Taesup Moon
mathjax: true
---

* content
{:toc}

##### Abstract
We propose DoPAMINE, a new neural network based multiplicative noise despeckling algorithm. Our algorithm is inspired by Neural AIDE (N-AIDE), which is a recently proposed neural adaptive image denoiser. While the original N-AIDE was designed for the additive noise case, we show that the same framework, i.e., adaptively learning a network for pixel-wise affine denoisers by minimizing an unbiased estimate of MSE, can be applied to the multiplicative noise case as well. Moreover, we derive a double-sided masked CNN architecture which can control the variance of the activation values in each layer and converge fast to high denoising performance during supervised training. In the experimental results, we show our DoPAMINE possesses high adaptivity via fine-tuning the network parameters based on the given noisy image and achieves significantly better despeckling results compared to SAR-DRN, a state-of-the-art CNN-based algorithm.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.02530](http://arxiv.org/abs/1902.02530)

##### PDF
[http://arxiv.org/pdf/1902.02530](http://arxiv.org/pdf/1902.02530)

