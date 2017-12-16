---
layout: post
title: "Improved Lossy Image Compression with Priming and Spatially Adaptive Bit Rates for Recurrent Networks"
date: 2017-03-29 16:12:12
categories: arXiv_CV
tags: arXiv_CV CNN
author: Nick Johnston, Damien Vincent, David Minnen, Michele Covell, Saurabh Singh, Troy Chinen, Sung Jin Hwang, Joel Shor, George Toderici
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a method for lossy image compression based on recurrent, convolutional neural networks that outperforms BPG (4:2:0 ), WebP, JPEG2000, and JPEG as measured by MS-SSIM. We introduce three improvements over previous research that lead to this state-of-the-art result. First, we show that training with a pixel-wise loss weighted by SSIM increases reconstruction quality according to several metrics. Second, we modify the recurrent architecture to improve spatial diffusion, which allows the network to more effectively capture and propagate image information through the network's hidden state. Finally, in addition to lossless entropy coding, we use a spatially adaptive bit allocation algorithm to more efficiently use the limited number of bits to encode visually complex image regions. We evaluate our method on the Kodak and Tecnick image sets and compare against standard codecs as well recently published methods based on deep neural networks.

##### Abstract (translated by Google)
我们提出了一种基于循环卷积神经网络的有损图像压缩方法，该方法胜过BPG（4：2：0），WebP，JPEG2000和JPEG，由MS-SSIM测量。我们介绍了三个改进，比以往的研究，导致这个最先进的成果。首先，我们表明，使用SSIM进行按像素方式的损失加权训练可以根据多个指标提高重建质量。其次，修改循环体系结构以改善空间扩散，使网络能够通过网络的隐藏状态更有效地捕获和传播图像信息。最后，除了无损熵编码之外，我们还使用空间自适应比特分配算法来更有效地使用有限数量的比特来对视觉上复杂的图像区域进行编码。我们在柯达和Tecnick图像集上评估我们的方法，并与标准编解码器以及最近发布的基于深度神经网络的方法进行比较。

##### URL
[https://arxiv.org/abs/1703.10114](https://arxiv.org/abs/1703.10114)

##### PDF
[https://arxiv.org/pdf/1703.10114](https://arxiv.org/pdf/1703.10114)

