---
layout: post
title: "Learning Deformable Kernels for Image and Video Denoising"
date: 2019-04-15 08:15:09
categories: arXiv_AI
tags: arXiv_AI Regularization
author: Xiangyu Xu, Muchen Li, Wenxiu Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Most of the classical denoising methods restore clear results by selecting and averaging pixels in the noisy input. Instead of relying on hand-crafted selecting and averaging strategies, we propose to explicitly learn this process with deep neural networks. Specifically, we propose deformable 2D kernels for image denoising where the sampling locations and kernel weights are both learned. The proposed kernel naturally adapts to image structures and could effectively reduce the oversmoothing artifacts. Furthermore, we develop 3D deformable kernels for video denoising to more efficiently sample pixels across the spatial-temporal space. Our method is able to solve the misalignment issues of large motion from dynamic scenes. For better training our video denoising model, we introduce the trilinear sampler and a new regularization term. We demonstrate that the proposed method performs favorably against the state-of-the-art image and video denoising approaches on both synthetic and real-world data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06903](http://arxiv.org/abs/1904.06903)

##### PDF
[http://arxiv.org/pdf/1904.06903](http://arxiv.org/pdf/1904.06903)

