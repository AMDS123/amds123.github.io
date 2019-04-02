---
layout: post
title: "COCO-GAN: Generation by Parts via Conditional Coordinating"
date: 2019-03-30 20:37:24
categories: arXiv_CV
tags: arXiv_CV GAN Inference Relation
author: Chieh Hubert Lin, Chia-Che Chang, Yu-Sheng Chen, Da-Cheng Juan, Wei Wei, Hwann-Tzong Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Humans can only interact with part of the surrounding environment due to biological restrictions. Therefore, we learn to reason the spatial relationships across a series of observations to piece together the surrounding environment. Inspired by such behavior and the fact that machines also have computational constraints, we propose \underline{CO}nditional \underline{CO}ordinate GAN (COCO-GAN) of which the generator generates images by parts based on their spatial coordinates as the condition. On the other hand, the discriminator learns to justify realism across multiple assembled patches by global coherence, local appearance, and edge-crossing continuity. Despite the full images are never generated during training, we show that COCO-GAN can produce \textbf{state-of-the-art-quality} full images during inference. We further demonstrate a variety of novel applications enabled by teaching the network to be aware of coordinates. First, we perform extrapolation to the learned coordinate manifold and generate off-the-boundary patches. Combining with the originally generated full image, COCO-GAN can produce images that are larger than training samples, which we called "beyond-boundary generation". We then showcase panorama generation within a cylindrical coordinate system that inherently preserves horizontally cyclic topology. On the computation side, COCO-GAN has a built-in divide-and-conquer paradigm that reduces memory requisition during training and inference, provides high-parallelism, and can generate parts of images on-demand.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.00284](http://arxiv.org/abs/1904.00284)

##### PDF
[http://arxiv.org/pdf/1904.00284](http://arxiv.org/pdf/1904.00284)

