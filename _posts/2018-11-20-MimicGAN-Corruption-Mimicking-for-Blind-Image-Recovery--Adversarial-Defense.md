---
layout: post
title: "MimicGAN: Corruption-Mimicking for Blind Image Recovery & Adversarial Defense"
date: 2018-11-20 20:59:38
categories: arXiv_AI
tags: arXiv_AI Adversarial Knowledge GAN
author: Rushil Anirudh, Jayaraman J. Thiagarajan, Bhavya Kailkhura, Timo Bremer
mathjax: true
---

* content
{:toc}

##### Abstract
Solving inverse problems continues to be a central challenge in computer vision. Existing techniques either explicitly construct an inverse mapping using prior knowledge about the corruption, or learn the inverse directly using a large collection of examples. However, in practice, the nature of corruption may be unknown, and thus it is challenging to regularize the problem of inferring a plausible solution. On the other hand, collecting task-specific training data is tedious for known corruptions and impossible for unknown ones. We present MimicGAN, an unsupervised technique to solve general inverse problems based on image priors in the form of generative adversarial networks (GANs). Using a GAN prior, we show that one can reliably recover solutions to underdetermined inverse problems through a surrogate network that learns to mimic the corruption at test time. Our system successively estimates the corruption and the clean image without the need for supervisory training, while outperforming existing baselines in blind image recovery. We also demonstrate that MimicGAN improves upon recent GAN-based defenses against adversarial attacks and represents one of the strongest test-time defenses available today.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08484](http://arxiv.org/abs/1811.08484)

##### PDF
[http://arxiv.org/pdf/1811.08484](http://arxiv.org/pdf/1811.08484)

