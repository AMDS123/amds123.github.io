---
layout: post
title: "Toward Convolutional Blind Denoising of Real Photographs"
date: 2019-04-19 07:05:40
categories: arXiv_CV
tags: arXiv_CV CNN Quantitative
author: Shi Guo, Zifei Yan, Kai Zhang, Wangmeng Zuo, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
While deep convolutional neural networks (CNNs) have achieved impressive success in image denoising with additive white Gaussian noise (AWGN), their performance remains limited on real-world noisy photographs. The main reason is that their learned models are easy to overfit on the simplified AWGN model which deviates severely from the complicated real-world noise model. In order to improve the generalization ability of deep CNN denoisers, we suggest training a convolutional blind denoising network (CBDNet) with more realistic noise model and real-world noisy-clean image pairs. On the one hand, both signal-dependent noise and in-camera signal processing pipeline is considered to synthesize realistic noisy images. On the other hand, real-world noisy photographs and their nearly noise-free counterparts are also included to train our CBDNet. To further provide an interactive strategy to rectify denoising result conveniently, a noise estimation subnetwork with asymmetric learning to suppress under-estimation of noise level is embedded into CBDNet. Extensive experimental results on three datasets of real-world noisy photographs clearly demonstrate the superior performance of CBDNet over state-of-the-arts in terms of quantitative metrics and visual quality. The code has been made available at https://github.com/GuoShi28/CBDNet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.04686](http://arxiv.org/abs/1807.04686)

##### PDF
[http://arxiv.org/pdf/1807.04686](http://arxiv.org/pdf/1807.04686)

