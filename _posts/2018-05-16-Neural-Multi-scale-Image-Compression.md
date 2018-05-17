---
layout: post
title: "Neural Multi-scale Image Compression"
date: 2018-05-16 16:00:01
categories: arXiv_CV
tags: arXiv_CV
author: Ken Nakanishi, Shin-ichi Maeda, Takeru Miyato, Daisuke Okanohara
mathjax: true
---

* content
{:toc}

##### Abstract
This study presents a new lossy image compression method that utilizes the multi-scale features of natural images. Our model consists of two networks: multi-scale lossy autoencoder and parallel multi-scale lossless coder. The multi-scale lossy autoencoder extracts the multi-scale image features to quantized variables and the parallel multi-scale lossless coder enables rapid and accurate lossless coding of the quantized variables via encoding/decoding the variables in parallel. Our proposed model achieves comparable performance to the state-of-the-art model on Kodak and RAISE-1k dataset images, and it encodes a PNG image of size $768 \times 512$ in 70 ms with a single GPU and a single CPU process and decodes it into a high-fidelity image in approximately 200 ms.

##### Abstract (translated by Google)
本研究提出了一种新的有损图像压缩方法，利用自然图像的多尺度特征。我们的模型由两个网络组成：多尺度有损自编码器和并行多尺度无损编码器。多尺度有损自动编码器将多尺度图像特征提取为量化变量，并行多尺度无损编码器通过并行编码/解码变量实现量化变量的快速和准确无损编码。我们提出的模型在柯达和RAISE-1k数据集图像上实现了与最先进的模型相媲美的性能，并且使用单个GPU和单个CPU进程在70 ms内对尺寸为$ 768 / times 512 $的PNG图像进行编码并在大约200毫秒内将其解码成高保真图像。

##### URL
[http://arxiv.org/abs/1805.06386](http://arxiv.org/abs/1805.06386)

##### PDF
[http://arxiv.org/pdf/1805.06386](http://arxiv.org/pdf/1805.06386)

