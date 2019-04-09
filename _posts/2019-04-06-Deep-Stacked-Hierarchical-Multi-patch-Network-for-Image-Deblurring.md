---
layout: post
title: "Deep Stacked Hierarchical Multi-patch Network for Image Deblurring"
date: 2019-04-06 15:15:36
categories: arXiv_CV
tags: arXiv_CV
author: Hongguang Zhang, Yuchao Dai, Hongdong Li, Piotr Koniusz
mathjax: true
---

* content
{:toc}

##### Abstract
Despite deep end-to-end learning methods have shown their superiority in removing non-uniform motion blur, there still exist major challenges with the current multi-scale and scale-recurrent models: 1) Deconvolution/upsampling operations in the coarse-to-fine scheme result in expensive runtime; 2) Simply increasing the model depth with finer-scale levels cannot improve the quality of deblurring. To tackle the above problems, we present a deep hierarchical multi-patch network inspired by Spatial Pyramid Matching to deal with blurry images via a fine-to-coarse hierarchical representation. To deal with the performance saturation w.r.t. depth, we propose a stacked version of our multi-patch model. Our proposed basic multi-patch model achieves the state-of-the-art performance on the GoPro dataset while enjoying a 40x faster runtime compared to current multi-scale methods. With 30ms to process an image at 1280x720 resolution, it is the first real-time deep motion deblurring model for 720p images at 30fps. For stacked networks, significant improvements (over 1.2dB) are achieved on the GoPro dataset by increasing the network depth. Moreover, by varying the depth of the stacked model, one can adapt the performance and runtime of the same network for different application scenarios.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03468](http://arxiv.org/abs/1904.03468)

##### PDF
[http://arxiv.org/pdf/1904.03468](http://arxiv.org/pdf/1904.03468)

