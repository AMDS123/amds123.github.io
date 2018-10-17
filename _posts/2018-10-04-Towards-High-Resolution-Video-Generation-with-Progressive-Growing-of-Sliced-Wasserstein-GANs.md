---
layout: post
title: "Towards High Resolution Video Generation with Progressive Growing of Sliced Wasserstein GANs"
date: 2018-10-04 20:41:48
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face Action_Recognition CNN Recognition
author: Dinesh Acharya, Zhiwu Huang, Danda Pani Paudel, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
The extension of image generation to video generation turns out to be a very difficult task, since the temporal dimension of videos introduces an extra challenge during the generation process. Besides, due to the limitation of memory and training stability, the generation becomes increasingly challenging with the increase of the resolution/duration of videos. In this work, we exploit the idea of progressive growing of Generative Adversarial Networks (GANs) for higher resolution video generation. In particular, we begin to produce video samples of low-resolution and short-duration, and then progressively increase both resolution and duration alone (or jointly) by adding new spatiotemporal convolutional layers to the current networks. Starting from the learning on a very raw-level spatial appearance and temporal movement of the video distribution, the proposed progressive method learns spatiotemporal information incrementally to generate higher resolution videos. Furthermore, we introduce a sliced version of Wasserstein GAN (SWGAN) loss to improve the distribution learning on the video data of high-dimension and mixed-spatiotemporal distribution. SWGAN loss replaces the distance between joint distributions by that of one-dimensional marginal distributions, making the loss easier to compute. We evaluate the proposed model on our collected face video dataset of 10,900 videos to generate photorealistic face videos of 256x256x32 resolution. In addition, our model also reaches a record inception score of 14.57 in unsupervised action recognition dataset UCF-101.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.02419](https://arxiv.org/abs/1810.02419)

##### PDF
[https://arxiv.org/pdf/1810.02419](https://arxiv.org/pdf/1810.02419)

