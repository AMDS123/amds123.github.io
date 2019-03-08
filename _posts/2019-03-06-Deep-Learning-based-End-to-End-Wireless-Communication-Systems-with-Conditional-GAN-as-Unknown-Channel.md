---
layout: post
title: "Deep Learning based End-to-End Wireless Communication Systems with Conditional GAN as Unknown Channel"
date: 2019-03-06 23:32:41
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN CNN Deep_Learning
author: Hao Ye, Le Liang, Geoffrey Ye Li, Biing-Hwang Fred Juang
mathjax: true
---

* content
{:toc}

##### Abstract
In this article, we develop an end-to-end wireless communication system using deep neural networks (DNNs), in which DNNs are employed to perform several key functions, including encoding, decoding, modulation, and demodulation. However, an accurate estimation of instantaneous channel transfer function, i.e., channel state information (CSI), is needed in order for the transmitter DNN to learn to optimize the receiver gain in decoding. This is very much a challenge since CSI varies with time and location in wireless communications and is hard to obtain when designing transceivers. We propose to use a conditional generative adversarial net (GAN) to represent channel effects and to bridge the transmitter DNN and the receiver DNN so that the gradient of the transmitter DNN can be back-propagated from the receiver DNN. In particular, a conditional GAN is employed to model the channel effects in a data-driven way, where the received signal corresponding to the pilot symbols is added as a part of the conditioning information of the GAN. To address the curse of dimensionality when the transmit symbol sequence is long, convolutional layers are utilized. From the simulation results, the proposed method is effective on additive white Gaussian noise (AWGN) channels, Rayleigh fading channels, and frequency-selective channels, which opens a new door for building data-driven DNNs for end-to-end communication systems.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.02551](https://arxiv.org/abs/1903.02551)

##### PDF
[https://arxiv.org/pdf/1903.02551](https://arxiv.org/pdf/1903.02551)

