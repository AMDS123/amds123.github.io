---
layout: post
title: "Learning Convolutional Networks for Content-weighted Image Compression"
date: 2017-09-19 11:23:26
categories: arXiv_CV
tags: arXiv_CV CNN Optimization
author: Mu Li, Wangmeng Zuo, Shuhang Gu, Debin Zhao, David Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Lossy image compression is generally formulated as a joint rate-distortion optimization to learn encoder, quantizer, and decoder. However, the quantizer is non-differentiable, and discrete entropy estimation usually is required for rate control. These make it very challenging to develop a convolutional network (CNN)-based image compression system. In this paper, motivated by that the local information content is spatially variant in an image, we suggest that the bit rate of the different parts of the image should be adapted to local content. And the content aware bit rate is allocated under the guidance of a content-weighted importance map. Thus, the sum of the importance map can serve as a continuous alternative of discrete entropy estimation to control compression rate. And binarizer is adopted to quantize the output of encoder due to the binarization scheme is also directly defined by the importance map. Furthermore, a proxy function is introduced for binary operation in backward propagation to make it differentiable. Therefore, the encoder, decoder, binarizer and importance map can be jointly optimized in an end-to-end manner by using a subset of the ImageNet database. In low bit rate image compression, experiments show that our system significantly outperforms JPEG and JPEG 2000 by structural similarity (SSIM) index, and can produce the much better visual result with sharp edges, rich textures, and fewer artifacts.

##### Abstract (translated by Google)
通常将有损图像压缩制定为联合率失真优化来学习编码器，量化器和解码器。然而，量化器是不可微分的，并且通常需要离散熵估计来进行速率控制。这使得开发基于卷积网络（CNN）的图像压缩系统非常具有挑战性。在本文中，由于本地信息内容在图像中是空间变化的，我们建议图像不同部分的比特率应适应本地内容。内容感知比特率在内容加权重要性映射的指导下分配。因此，重要性图的和可以作为离散熵估计的连续替代来控制压缩率。由于二值化方案也是由重要性图直接定义的，因此采用二值化器来量化编码器的输出。此外，在后向传播中引入二进制操作的代理函数，使其可区分。因此，编码器，解码器，二值化器和重要性映射可以通过使用ImageNet数据库的子集以端对端的方式进行联合优化。在低比特率图像压缩方面，实验表明，我们的系统通过结构相似性（SSIM）指数明显优于JPEG和JPEG2000，并且能够产生更好的视觉效果，边缘清晰，纹理丰富，伪影更少。

##### URL
[https://arxiv.org/abs/1703.10553](https://arxiv.org/abs/1703.10553)

##### PDF
[https://arxiv.org/pdf/1703.10553](https://arxiv.org/pdf/1703.10553)

