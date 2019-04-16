---
layout: post
title: "Learning from Multi-domain Artistic Images for Arbitrary Style Transfer"
date: 2019-04-14 06:22:51
categories: arXiv_CV
tags: arXiv_CV Adversarial Style_Transfer Quantitative
author: Zheng Xu, Michael Wilber, Chen Fang, Aaron Hertzmann, Hailin Jin
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a fast feed-forward network for arbitrary style transfer, which can generate stylized image for previously unseen content and style image pairs. Besides the traditional content and style representation based on deep features and statistics for textures, we use adversarial networks to regularize the generation of stylized images. Our adversarial network learns the intrinsic property of image styles from large-scale multi-domain artistic images. The adversarial training is challenging because both the input and output of our generator are diverse multi-domain images. We use a conditional generator that stylized content by shifting the statistics of deep features, and a conditional discriminator based on the coarse category of styles. Moreover, we propose a mask module to spatially decide the stylization level and stabilize adversarial training by avoiding mode collapse. As a side effect, our trained discriminator can be applied to rank and select representative stylized images. We qualitatively and quantitatively evaluate the proposed method, and compare with recent style transfer methods. We release our code and model at https://github.com/nightldj/behance_release.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.09987](http://arxiv.org/abs/1805.09987)

##### PDF
[http://arxiv.org/pdf/1805.09987](http://arxiv.org/pdf/1805.09987)

