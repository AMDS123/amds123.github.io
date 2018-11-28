---
layout: post
title: "Adversarial Video Compression Guided by Soft Edge Detection"
date: 2018-11-26 20:22:04
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection GAN Detection
author: Sungsoo Kim, Jin Soo Park, Christos G. Bampis, Jaeseong Lee, Mia K. Markey, Alexandros G. Dimakis, Alan C. Bovik
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a video compression framework using conditional Generative Adversarial Networks (GANs). We rely on two encoders: one that deploys a standard video codec and another which generates low-level maps via a pipeline of down-sampling, a newly devised soft edge detector, and a novel lossless compression scheme. For decoding, we use a standard video decoder as well as a neural network based one, which is trained using a conditional GAN. Recent "deep" approaches to video compression require multiple videos to pre-train generative networks to conduct interpolation. In contrast to this prior work, our scheme trains a generative decoder on pairs of a very limited number of key frames taken from a single video and corresponding low-level maps. The trained decoder produces reconstructed frames relying on a guidance of low-level maps, without any interpolation. Experiments on a diverse set of 131 videos demonstrate that our proposed GAN-based compression engine achieves much higher quality reconstructions at very low bitrates than prevailing standard codecs such as H.264 or HEVC.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.10673](http://arxiv.org/abs/1811.10673)

##### PDF
[http://arxiv.org/pdf/1811.10673](http://arxiv.org/pdf/1811.10673)

