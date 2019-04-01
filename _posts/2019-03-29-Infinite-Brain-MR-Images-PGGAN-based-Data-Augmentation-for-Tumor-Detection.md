---
layout: post
title: "Infinite Brain MR Images: PGGAN-based Data Augmentation for Tumor Detection"
date: 2019-03-29 15:16:15
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN CNN Detection
author: Changhee Han, Leonardo Rundo, Ryosuke Araki, Yujiro Furukawa, Giancarlo Mauri, Hideki Nakayama, Hideaki Hayashi
mathjax: true
---

* content
{:toc}

##### Abstract
Due to the lack of available annotated medical images, accurate computer-assisted diagnosis requires intensive Data Augmentation (DA) techniques, such as geometric/intensity transformations of original images; however, those transformed images intrinsically have a similar distribution to the original ones, leading to limited performance improvement. To fill the data lack in the real image distribution, we synthesize brain contrast-enhanced Magnetic Resonance (MR) images---realistic but completely different from the original ones---using Generative Adversarial Networks (GANs). This study exploits Progressive Growing of GANs (PGGANs), a multi-stage generative training method, to generate original-sized 256 X 256 MR images for Convolutional Neural Network-based brain tumor detection, which is challenging via conventional GANs; difficulties arise due to unstable GAN training with high resolution and a variety of tumors in size, location, shape, and contrast. Our preliminary results show that this novel PGGAN-based DA method can achieve promising performance improvement, when combined with classical DA, in tumor detection and also in other medical imaging tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.12564](http://arxiv.org/abs/1903.12564)

##### PDF
[http://arxiv.org/pdf/1903.12564](http://arxiv.org/pdf/1903.12564)

