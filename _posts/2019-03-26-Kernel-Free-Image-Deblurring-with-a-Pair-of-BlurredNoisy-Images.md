---
layout: post
title: "Kernel-Free Image Deblurring with a Pair of Blurred/Noisy Images"
date: 2019-03-26 03:47:03
categories: arXiv_CV
tags: arXiv_CV Quantitative
author: Chunzhi Gu, Xuequan Lu, Ying He, Chao Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Complex blur like the mixup of space-variant and space-invariant blur, which is hard to be modeled mathematically, widely exists in real images. In the real world, a common type of blur occurs when capturing images in low-light environments. In this paper, we propose a novel image deblurring method that does not need to estimate blur kernels. We utilize a pair of images which can be easily acquired in low-light situations: (1) a blurred image taken with low shutter speed and low ISO noise, and (2) a noisy image captured with high shutter speed and high ISO noise. Specifically, the blurred image is first sliced into patches, and we extend the Gaussian mixture model (GMM) to model the underlying intensity distribution of each patch using the corresponding patches in the noisy image. We compute patch correspondences by analyzing the optical flow between the two images. The Expectation-Maximization (EM) algorithm is utilized to estimate the involved parameters in the GMM. To preserve sharp features, we add an additional bilateral term to the objective function in the M-step. We eventually add a detail layer to the deblurred image for refinement. Extensive experiments on both synthetic and real-world data demonstrate that our method outperforms state-of-the-art techniques, in terms of robustness, visual quality and quantitative metrics. We will make our dataset and source code publicly available.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10667](http://arxiv.org/abs/1903.10667)

##### PDF
[http://arxiv.org/pdf/1903.10667](http://arxiv.org/pdf/1903.10667)

