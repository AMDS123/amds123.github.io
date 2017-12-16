---
layout: post
title: "CISRDCNN: Super-resolution of compressed images using deep convolutional neural networks"
date: 2017-09-19 02:45:12
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Knowledge CNN
author: Honggang Chen, Xiaohai He, Chao Ren, Linbo Qing, Qizhi Teng
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, much research has been conducted on image super-resolution (SR). To the best of our knowledge, however, few SR methods were concerned with compressed images. The SR of compressed images is a challenging task due to the complicated compression artifacts, while many images suffer from them in practice. The intuitive solution for this difficult task is to decouple it into two sequential but independent subproblems, i.e., compression artifacts reduction (CAR) and SR. Nevertheless, some useful details may be removed in CAR stage, which is contrary to the goal of SR and makes the SR stage more challenging. In this paper, an end-to-end trainable deep convolutional neural network is designed to perform SR on compressed images (CISRDCNN), which reduces compression artifacts and improves image resolution jointly. Experiments on compressed images produced by JPEG (we take the JPEG as an example in this paper) demonstrate that the proposed CISRDCNN yields state-of-the-art SR performance on commonly used test images and imagesets. The results of CISRDCNN on real low quality web images are also very impressive, with obvious quality enhancement. Further, we explore the application of the proposed SR method in low bit-rate image coding, leading to better rate-distortion performance than JPEG.

##### Abstract (translated by Google)
近年来，对图像超分辨率（SR）进行了大量研究。然而据我们所知，很少有SR方法涉及压缩图像。压缩图像的SR由于复杂的压缩伪像而是一项具有挑战性的任务，而在实践中许多图像受到它们的困扰。这个困难任务的直观解决方案是将其解耦成两个连续但独立的子问题，即压缩伪像减少（CAR）和SR。然而，在CAR阶段可能会删除一些有用的细节，这与SR的目标背道而驰，并使SR阶段更具挑战性。本文设计了一种端到端的可训练深度卷积神经网络，在压缩图像上执行SR（CISRDCNN），减少压缩伪像，提高图像分辨率。对JPEG产生的压缩图像的实验（本文以JPEG为例）表明，所提出的CISRDCNN在常用的测试图像和图像集上获得了最先进的SR性能。 CISRDCNN对真实低质量网页图像的结果也非常令人印象深刻，质量明显提高。此外，我们探索了所提出的SR方法在低比特率图像编码中的应用，导致比JPEG更好的速率失真性能。

##### URL
[https://arxiv.org/abs/1709.06229](https://arxiv.org/abs/1709.06229)

##### PDF
[https://arxiv.org/pdf/1709.06229](https://arxiv.org/pdf/1709.06229)

