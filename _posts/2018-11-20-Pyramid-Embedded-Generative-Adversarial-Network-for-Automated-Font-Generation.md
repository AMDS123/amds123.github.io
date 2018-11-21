---
layout: post
title: "Pyramid Embedded Generative Adversarial Network for Automated Font Generation"
date: 2018-11-20 07:37:46
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Quantitative
author: Donghui Sun, Qing Zhang, Jun Yang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we investigate the Chinese font synthesis problem and propose a Pyramid Embedded Generative Adversarial Network (PEGAN) to automatically generate Chinese character images. The PEGAN consists of one generator and one discriminator. The generator is built using one encoder-decoder structure with cascaded refinement connections and mirror skip connections. The cascaded refinement connections embed a multiscale pyramid of downsampled original input into the encoder feature maps of different layers, and multi-scale feature maps from the encoder are connected to the corresponding feature maps in the decoder to make the mirror skip connections. Through combining the generative adversarial loss, pixel-wise loss, category loss and perceptual loss, the generator and discriminator can be trained alternately to synthesize character images. In order to verify the effectiveness of our proposed PEGAN, we first build one evaluation set, in which the characters are selected according to their stroke number and frequency of use, and then use both qualitative and quantitative metrics to measure the performance of our model comparing with the baseline method. The experimental results demonstrate the effectiveness of our proposed model, it shows the potential to automatically extend small font banks into complete ones.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08106](http://arxiv.org/abs/1811.08106)

##### PDF
[http://arxiv.org/pdf/1811.08106](http://arxiv.org/pdf/1811.08106)

