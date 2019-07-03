---
layout: post
title: "Learnable Gated Temporal Shift Module for Deep Video Inpainting"
date: 2019-07-02 02:38:24
categories: arXiv_CV
tags: arXiv_CV Face Inference
author: Ya-Liang Chang, Zhe Yu Liu, Kuan-Ying Lee, Winston Hsu
mathjax: true
---

* content
{:toc}

##### Abstract
How to efficiently utilize temporal information to recover videos in a consistent way is the main issue for video inpainting problems. Conventional 2D CNNs have achieved good performance on image inpainting but often lead to temporally inconsistent results where frames will flicker when applied to videos (see https://www.youtube.com/watch?v=87Vh1HDBjD0&amp;list=PLPoVtv-xp_dL5uckIzz1PKwNjg1yI0I94&amp;index=1); 3D CNNs can capture temporal information but are computationally intensive and hard to train. In this paper, we present a novel component termed Learnable Gated Temporal Shift Module (LGTSM) for video inpainting models that could effectively tackle arbitrary video masks without additional parameters from 3D convolutions. LGTSM is designed to let 2D convolutions make use of neighboring frames more efficiently, which is crucial for video inpainting. Specifically, in each layer, LGTSM learns to shift some channels to its temporal neighbors so that 2D convolutions could be enhanced to handle temporal information. Meanwhile, a gated convolution is applied to the layer to identify the masked areas that are poisoning for conventional convolutions. On the FaceForensics and Free-form Video Inpainting (FVI) dataset, our model achieves state-of-the-art results with simply 33% of parameters and inference time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.01131](http://arxiv.org/abs/1907.01131)

##### PDF
[http://arxiv.org/pdf/1907.01131](http://arxiv.org/pdf/1907.01131)

