---
layout: post
title: "Toward Joint Image Generation and Compression using Generative Adversarial Networks"
date: 2019-01-23 12:07:43
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Byeongkeun Kang, Subarna Tripathi, Truong Q. Nguyen
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a generative adversarial network framework that generates compressed images instead of synthesizing raw RGB images and compressing them separately. In the real world, most images and videos are stored and transferred in a compressed format to save storage capacity and data transfer bandwidth. However, since typical generative adversarial networks generate raw RGB images, those generated images need to be compressed by a post-processing stage to reduce the data size. Among image compression methods, JPEG has been one of the most commonly used lossy compression methods for still images. Hence, we propose a novel framework that generates JPEG compressed images using generative adversarial networks. The novel generator consists of the proposed locally connected layers, chroma subsampling layers, quantization layers, residual blocks, and convolution layers. The locally connected layer is proposed to enable block-based operations. We also discuss training strategies for the proposed architecture including the loss function and the transformation between its generator and its discriminator. The proposed method is evaluated using the publicly available CIFAR-10 dataset and LSUN bedroom dataset. The results demonstrate that the proposed method is able to generate compressed data with competitive qualities. The proposed method is a promising baseline method for joint image generation and compression using generative adversarial networks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.07838](http://arxiv.org/abs/1901.07838)

##### PDF
[http://arxiv.org/pdf/1901.07838](http://arxiv.org/pdf/1901.07838)

