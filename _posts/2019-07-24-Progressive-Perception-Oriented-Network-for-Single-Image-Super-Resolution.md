---
layout: post
title: "Progressive Perception-Oriented Network for Single Image Super-Resolution"
date: 2019-07-24 12:43:35
categories: arXiv_CV
tags: arXiv_CV Adversarial Super_Resolution GAN Quantitative
author: Zheng Hui, Jie Li, Xinbo Gao, Xiumei Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, it has been shown that deep neural networks can significantly improve the performance of single image super-resolution (SISR). Numerous studies have focused on raising the quantitative quality of super-resolved (SR) images. However, these methods that target PSNR maximization usually produce smooth images at large upscaling factor. The introduction of generative adversarial networks (GANs) can mitigate this issue and show impressive results with synthetic high-frequency textures. Nevertheless, these GAN-based approaches always tend to add fake textures and even artifacts to make the SR image of visually higher-resolution. In this paper, we propose a novel perceptual image super-resolution method that progressively generates visually high-quality results by constructing a stage-wise network. Specifically, the first phase concentrates on minimizing pixel-wise error and the second stage utilizes the features extracted by the previous stage to pursue results with better structural retention. The final stage employs fine structure features distilled by the second phase to produce more realistic results. In this way, we can maintain the pixel and structure level information in the perceptual image as much as possible. It is worth note that the proposed method can build three types of images in a feed-forward process. Also, we explore a new generator that adopts multi-scale hierarchical features fusion. Extensive experiments on benchmark datasets show that our approach is superior to the state-of-the-art methods. Code is available at https://github.com/Zheng222/PPON.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.10399](http://arxiv.org/abs/1907.10399)

##### PDF
[http://arxiv.org/pdf/1907.10399](http://arxiv.org/pdf/1907.10399)

