---
layout: post
title: "Multi-scale GANs for Memory-efficient Generation of High Resolution Medical Images"
date: 2019-07-02 13:59:24
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Hristina Uzunova, Fabian Jacob, Alex Frydrychowicz, Heinz Handels, Jan Ehrhardt
mathjax: true
---

* content
{:toc}

##### Abstract
Currently generative adversarial networks (GANs) are rarely applied to medical images of large sizes, especially 3D volumes, due to their large computational demand. We propose a novel multi-scale patch-based GAN approach to generate large high resolution 2D and 3D images. Our key idea is to first learn a low-resolution version of the image and then generate patches of successively growing resolutions conditioned on previous scales. In a domain translation use-case scenario, 3D thorax CTs of size 512x512x512 and thorax X-rays of size 2048x2048 are generated and we show that, due to the constant GPU memory demand of our method, arbitrarily large images of high resolution can be generated. Moreover, compared to common patch-based approaches, our multi-resolution scheme enables better image quality and prevents patch artifacts.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.01376](http://arxiv.org/abs/1907.01376)

##### PDF
[http://arxiv.org/pdf/1907.01376](http://arxiv.org/pdf/1907.01376)

