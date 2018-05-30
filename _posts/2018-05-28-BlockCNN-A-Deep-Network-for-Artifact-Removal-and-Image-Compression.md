---
layout: post
title: "BlockCNN: A Deep Network for Artifact Removal and Image Compression"
date: 2018-05-28 17:29:48
categories: arXiv_CV
tags: arXiv_CV
author: Danial Maleki, Soheila Nadalian, Mohammad Mahdi Derakhshani, Mohammad Amin Sadeghi
mathjax: true
---

* content
{:toc}

##### Abstract
We present a general technique that performs both artifact removal and image compression. For artifact removal, we input a JPEG image and try to remove its compression artifacts. For compression, we input an image and process its 8 by 8 blocks in a sequence. For each block, we first try to predict its intensities based on previous blocks; then, we store a residual with respect to the input image. Our technique reuses JPEG's legacy compression and decompression routines. Both our artifact removal and our image compression techniques use the same deep network, but with different training weights. Our technique is simple and fast and it significantly improves the performance of artifact removal and image compression.

##### Abstract (translated by Google)
我们提出了执行伪像去除和图像压缩的通用技术。为了去除伪像，我们输入一个JPEG图像并尝试去除其压缩伪像。对于压缩，我们输入一个图像并按顺序处理它的8乘8块。对于每个区块，我们首先尝试根据之前的区块预测其强度;然后，我们存储相对于输入图像的残差。我们的技术重用了JPEG的传统压缩和解压缩例程。我们的伪像去除和我们的图像压缩技术都使用相同的深度网络，但具有不同的训练权重。我们的技术简单快速，显着提高了伪像去除和图像压缩的性能。

##### URL
[http://arxiv.org/abs/1805.11091](http://arxiv.org/abs/1805.11091)

##### PDF
[http://arxiv.org/pdf/1805.11091](http://arxiv.org/pdf/1805.11091)

