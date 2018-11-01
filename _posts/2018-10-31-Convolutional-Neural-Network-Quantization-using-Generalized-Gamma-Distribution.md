---
layout: post
title: "Convolutional Neural Network Quantization using Generalized Gamma Distribution"
date: 2018-10-31 15:17:05
categories: arXiv_AI
tags: arXiv_AI CNN
author: Doyun Kim, Han Young Yim, Sanghyuck Ha, Changgwun Lee, Inyup Kang
mathjax: true
---

* content
{:toc}

##### Abstract
As edge applications using convolutional neural networks (CNN) models grow, it is becoming necessary to introduce dedicated hardware accelerators in which network parameters and feature-map data are represented with limited precision. In this paper we propose a novel quantization algorithm for energy-efficient deployment of the hardware accelerators. For weights and biases, the optimal bit length of the fractional part is determined so that the quantization error is minimized over their distribution. For feature-map data, meanwhile, their sample distribution is well approximated with the generalized gamma distribution (GGD), and accordingly the optimal quantization step size can be obtained through the asymptotical closed form solution of GGD. The proposed quantization algorithm has a higher signal-to-quantization-noise ratio (SQNR) than other quantization schemes previously proposed for CNNs, and even can be more improved by tuning the quantization parameters, resulting in efficient implementation of the hardware accelerators for CNNs in terms of power consumption and memory bandwidth.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.13329](http://arxiv.org/abs/1810.13329)

##### PDF
[http://arxiv.org/pdf/1810.13329](http://arxiv.org/pdf/1810.13329)

