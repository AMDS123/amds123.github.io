---
layout: post
title: "Customized OCT images compression scheme with deep neural network"
date: 2019-08-24 21:38:29
categories: arXiv_CV
tags: arXiv_CV GAN CNN
author: Pengfei Guo, Dawei Li, Xingde Li
mathjax: true
---

* content
{:toc}

##### Abstract
We customize an end-to-end image compression framework for retina OCT images based on deep convolutional neural networks (CNNs). The customized compression scheme consists of three parts: data Preprocessing, compression CNNs, and reconstruction CNNs. Data preprocessing module reduces the speckle noise of the OCT images and the segments out the region of interest. We added customized skip connections between the compression CNNs and the reconstruction CNNs to reserve the detail information and trained the two nets together with the semantic segmented image patches from data preprocessing module. To train the two networks sensitive to both low frequency information and high frequency information, we adopted an objective function with two parts: A PatchGAN discriminator to judge the high frequency information and a differentiable MS-SSIM penalty to evaluate the low frequency information. The proposed framework was trained and evaluated on a publicly available OCT dataset. The evaluation showed above 99% similarity in terms of multi-scale structural similarity (MS-SSIM) when the compression ratio is as high as 40. Furthermore, the reconstructed images of compression ratio 80 from the proposed framework even have better quality than that of compression ratio 20 from JPEG by visual comparison. The testing result outperforms JPEG in term of both of MS-SSIM and visualization, which is more obvious as the increase of compression ratio. Our preliminary result indicates the huge potential of deep neural networks on customized medical image compression.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09215](http://arxiv.org/abs/1908.09215)

##### PDF
[http://arxiv.org/pdf/1908.09215](http://arxiv.org/pdf/1908.09215)

