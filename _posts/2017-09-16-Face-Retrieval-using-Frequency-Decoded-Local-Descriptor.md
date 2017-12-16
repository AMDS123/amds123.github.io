---
layout: post
title: "Face Retrieval using Frequency Decoded Local Descriptor"
date: 2017-09-16 06:43:59
categories: arXiv_CV
tags: arXiv_CV Face Relation
author: Shiv Ram Dubey
mathjax: true
---

* content
{:toc}

##### Abstract
The local descriptors have been the backbone of most of the computer vision problems. Most of the existing local descriptors are generated over the raw input images. In order to increase the discriminative power of the local descriptors, some researchers converted the raw image into multiple images with the help some high and low pass frequency filters, then the local descriptors are computed over each filtered image and finally concatenated into a single descriptor. By doing so, these approaches do not utilize the inter frequency relationship which causes the less improvement in the discriminative power of the descriptor that could be achieved. In this paper, this problem is solved by utilizing the decoder concept of multi-channel decoded local binary pattern over the multi-frequency patterns. A frequency decoded local binary pattern (FDLBP) is proposed with two decoders. Each decoder works with one low frequency pattern and two high frequency pattern. Finally, the descriptors from both decoders are concatenated to form the single descriptor. The face retrieval experiments are conducted over four benchmarks and challenging databases such as PaSC, LFW, PubFig, and ESSEX. The experimental results confirm the superiority of the FDLBP descriptor as compared to the state-of-the-art descriptors such as LBP, SOBEL_LBP, BoF_LBP, SVD_S_LBP, mdLBP, etc.

##### Abstract (translated by Google)
局部描述符一直是大多数计算机视觉问题的支柱。大多数现有的本地描述符是在原始输入图像上生成的。为了增加局部描述符的判别能力，一些研究人员利用一些高通滤波器和低通滤波器将原始图像转换成多个图像，然后在每个滤波图像上计算局部描述符，最后连接成一个描述符。通过这样做，这些方法不利用频率间关系，这导致可以实现的描述符的判别力的改善较小。在这篇文章中，这个问题是通过利用解码器在多频率模式上的多通道解码局部二进制模式来解决的。提出了一种频率解码局部二进制码型（FDLBP）和两个解码器。每个解码器都有一个低频模式和两个高频模式。最后，来自两个解码器的描述符被连接起来形成单个描述符。人脸检索实验是通过四个基准和具有挑战性的数据库进行的，如PaSC，LFW，PubFig和ESSEX。实验结果证实了与LBP，SOBEL_LBP，BoF_LBP，SVD_S_LBP，mdLBP等最先进的描述符相比，FDLBP描述符的优越性。

##### URL
[https://arxiv.org/abs/1709.06508](https://arxiv.org/abs/1709.06508)

##### PDF
[https://arxiv.org/pdf/1709.06508](https://arxiv.org/pdf/1709.06508)

