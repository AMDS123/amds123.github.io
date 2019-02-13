---
layout: post
title: "GAN- vs. JPEG2000 Image Compression for Distributed Automotive Perception: Higher Peak SNR Does Not Mean Better Semantic Segmentation"
date: 2019-02-12 10:09:37
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN Semantic_Segmentation
author: Jonas L&#xf6;hdefink, Andreas B&#xe4;r, Nico M. Schmidt, Fabian H&#xfc;ger, Peter Schlicht, Tim Fingscheidt
mathjax: true
---

* content
{:toc}

##### Abstract
The high amount of sensors required for autonomous driving poses enormous challenges on the capacity of automotive bus systems. There is a need to understand tradeoffs between bitrate and perception performance. In this paper, we compare the image compression standards JPEG, JPEG2000, and WebP to a modern encoder/decoder image compression approach based on generative adversarial networks (GANs). We evaluate both the pure compression performance using typical metrics such as peak signal-to-noise ratio (PSNR), structural similarity (SSIM) and others, but also the performance of a subsequent perception function, namely a semantic segmentation (characterized by the mean intersection over union (mIoU) measure). Not surprisingly, for all investigated compression methods, a higher bitrate means better results in all investigated quality metrics. Interestingly, however, we show that the semantic segmentation mIoU of the GAN autoencoder in the highly relevant low-bitrate regime (at 0.0625 bit/pixel) is better by 3.9% absolute than JPEG2000, although the latter still is considerably better in terms of PSNR (5.91 dB difference). This effect can greatly be enlarged by training the semantic segmentation model with images originating from the decoder, so that the mIoU using the segmentation model trained by GAN reconstructions exceeds the use of the model trained with original images by almost 20% absolute. We conclude that distributed perception in future autonomous driving will most probably not provide a solution to the automotive bus capacity bottleneck by using standard compression schemes such as JPEG2000, but requires modern coding approaches, with the GAN encoder/decoder method being a promising candidate.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.04311](http://arxiv.org/abs/1902.04311)

##### PDF
[http://arxiv.org/pdf/1902.04311](http://arxiv.org/pdf/1902.04311)

