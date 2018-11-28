---
layout: post
title: "Label-Noise Robust Generative Adversarial Networks"
date: 2018-11-27 18:56:21
categories: arXiv_CV
tags: arXiv_CV Adversarial Attention GAN Classification
author: Takuhiro Kaneko, Yoshitaka Ushiku, Tatsuya Harada
mathjax: true
---

* content
{:toc}

##### Abstract
Generative adversarial networks (GANs) are a framework that learns a generative distribution through adversarial training. Recently, their class conditional extensions (e.g., conditional GAN (cGAN) and auxiliary classifier GAN (AC-GAN)) have attracted much attention owing to their ability to learn the disentangled representations and to improve the training stability. However, their training requires the availability of large-scale accurate class-labeled data, which are often laborious or impractical to collect in a real-world scenario. To remedy the drawback, we propose a novel family of GANs called label-noise robust GANs (rGANs), which, by incorporating a noise transition model, can learn a clean label conditional generative distribution even when training labels are noisy. In particular, we propose two variants: rAC-GAN, which is a bridging model between AC-GAN and the noise-robust classification model, and rcGAN, which is an extension of cGAN and is guaranteed to learn the clean label conditional distribution in an optimal condition. In addition to providing the theoretical background, we demonstrate the effectiveness of our models through extensive experiments using diverse GAN configurations, various noise settings, and multiple evaluation metrics (in which we tested 402 patterns in total).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11165](http://arxiv.org/abs/1811.11165)

##### PDF
[http://arxiv.org/pdf/1811.11165](http://arxiv.org/pdf/1811.11165)

