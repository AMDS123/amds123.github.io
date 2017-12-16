---
layout: post
title: "A multi-layer image representation using Regularized Residual Quantization: application to compression and denoising"
date: 2017-07-07 14:28:21
categories: arXiv_CV
tags: arXiv_CV Image_Caption
author: Sohrab Ferdowsi, Slava Voloshynovskiy, Dimche Kostadinov
mathjax: true
---

* content
{:toc}

##### Abstract
A learning-based framework for representation of domain-specific images is proposed where joint compression and denoising can be done using a VQ-based multi-layer network. While it learns to compress the images from a training set, the compression performance is very well generalized on images from a test set. Moreover, when fed with noisy versions of the test set, since it has priors from clean images, the network also efficiently denoises the test images during the reconstruction. The proposed framework is a regularized version of the Residual Quantization (RQ) where at each stage, the quantization error from the previous stage is further quantized. Instead of codebook learning from the k-means which over-trains for high-dimensional vectors, we show that only generating the codewords from a random, but properly regularized distribution suffices to compress the images globally and without the need to resort to patch-based division of images. The experiments are done on the \textit{CroppedYale-B} set of facial images and the method is compared with the JPEG-2000 codec for compression and BM3D for denoising, showing promising results.

##### Abstract (translated by Google)
提出了一个基于学习的表示域特定图像的框架，其中可以使用基于VQ的多层网络进行联合压缩和去噪。当学习压缩训练集中的图像时，压缩性能在测试集的图像上得到很好的推广。而且，当使用噪声版本的测试集时，由于它具有清晰图像的先验性，因此网络在重建期间也有效地对测试图像进​​行去噪。所提出的框架是剩余量化（RQ）的正则化版本，其中在每个阶段，来自前一阶段的量化误差被进一步量化。而不是从高维矢量过度训练的k-means中学习码本，我们表明只从随机生成码字，但是适当正则化的分布足以在全局上压缩图像，而不需要求助于基于补丁图像的分割。实验在\ textit {CroppedYale-B}面部图像集上进行，并将该方法与用于压缩的JPEG-2000编解码器和用于去噪的BM3D进行比较，显示出有希望的结果。

##### URL
[https://arxiv.org/abs/1707.02194](https://arxiv.org/abs/1707.02194)

##### PDF
[https://arxiv.org/pdf/1707.02194](https://arxiv.org/pdf/1707.02194)

