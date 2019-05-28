---
layout: post
title: "GAN2GAN: Generative Noise Learning for Blind Image Denoising with Single Noisy Images"
date: 2019-05-25 00:16:09
categories: arXiv_CV
tags: arXiv_CV GAN
author: Sungmin Cha, Taeeon Park, Taesup Moon
mathjax: true
---

* content
{:toc}

##### Abstract
We tackle a challenging blind image denoising problem, in which only single noisy images are available for training a denoiser and no information about noise is known, except for it being zero-mean, additive, and independent of the clean image. In such a setting, which often occurs in practice, it is not possible to train a denoiser with the standard discriminative training or with the recently developed Noise2Noise (N2N) training; the former requires the underlying clean image for the given noisy image, and the latter requires two independently realized noisy image pair for a clean image. To that end, we propose GAN2GAN (Generated-Artificial-Noise to Generated-Artificial-Noise) method that can first learn to generate synthetic noisy image pairs that simulate independent realizations of the noise in the given images, then carry out the N2N training of a denoiser with those synthetically generated noisy image pairs. Our method consists of three parts: extracting smooth noisy patches to learn the noise distribution in the given images, training a generative model to synthesize the noisy image pairs, and devising an iterative N2N training of a denoiser. In results, we show the denoiser trained with our GAN2GAN, solely based on single noisy images, achieves an impressive denoising performance, almost approaching the performance of the standard discriminatively-trained or N2N-trained models that have more information than ours, and significantly outperforming the recent baselines for the same setting.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10488](http://arxiv.org/abs/1905.10488)

##### PDF
[http://arxiv.org/pdf/1905.10488](http://arxiv.org/pdf/1905.10488)

