---
layout: post
title: "When AWGN-based Denoiser Meets Real Noises"
date: 2019-04-06 16:16:49
categories: arXiv_CV
tags: arXiv_CV
author: Yuqian Zhou, Jianbo Jiao, Haibin Huang, Yang Wang, Jue Wang, Honghui Shi, Thomas Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Discriminative learning based image denoisers have achieved promising performance on synthetic noise such as the additive Gaussian noise. However, their performance on images with real noise is often not satisfactory. The main reason is that real noises are mostly spatially/channel-correlated and spatial/channel-variant. In contrast, the synthetic Additive White Gaussian Noise (AWGN) adopted in most previous work is pixel-independent. In this paper, we propose a novel approach to boost the performance of a real image denoiser which is trained only with synthetic pixel-independent noise data. First, we train a deep model that consists of a noise estimator and a denoiser with mixed AWGN and Random Value Impulse Noise (RVIN). We then investigate Pixel-shuffle Down-sampling (PD) strategy to adapt the trained model to real noises. Extensive experiments demonstrate the effectiveness and generalization ability of the proposed approach. Notably, our method achieves state-of-the-art performance on real sRGB images in the DND benchmark. Codes are available at https://github.com/yzhouas/PD-Denoising-pytorch.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03485](http://arxiv.org/abs/1904.03485)

##### PDF
[http://arxiv.org/pdf/1904.03485](http://arxiv.org/pdf/1904.03485)

