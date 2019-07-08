---
layout: post
title: "High-throughput Onboard Hyperspectral Image Compression with Ground-based CNN Reconstruction"
date: 2019-07-05 17:59:25
categories: arXiv_CV
tags: arXiv_CV CNN Prediction
author: Diego Valsesia, Enrico Magli
mathjax: true
---

* content
{:toc}

##### Abstract
Compression of hyperspectral images onboard of spacecrafts is a tradeoff between the limited computational resources and the ever-growing spatial and spectral resolution of the optical instruments. As such, it requires low-complexity algorithms with good rate-distortion performance and high throughput. In recent years, the Consultative Committee for Space Data Systems (CCSDS) has focused on lossless and near-lossless compression approaches based on predictive coding, resulting in the recently published CCSDS 123.0-B-2 recommended standard. While the in-loop reconstruction of quantized prediction residuals provides excellent rate-distortion performance for the near-lossless operating mode, it significantly constrains the achievable throughput due to data dependencies. In this paper, we study the performance of a faster method based on prequantization of the image followed by a lossless predictive compressor. While this is well known to be suboptimal, one can exploit powerful signal models to reconstruct the image at the ground segment, recovering part of the suboptimality. In particular, we show that convolutional neural networks can be used for this task and that they can recover the whole SNR drop incurred at a bitrate of 2 bits per pixel.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.02959](http://arxiv.org/abs/1907.02959)

##### PDF
[http://arxiv.org/pdf/1907.02959](http://arxiv.org/pdf/1907.02959)

