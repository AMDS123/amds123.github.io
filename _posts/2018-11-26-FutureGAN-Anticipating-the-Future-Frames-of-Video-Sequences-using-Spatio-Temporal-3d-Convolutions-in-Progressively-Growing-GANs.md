---
layout: post
title: "FutureGAN: Anticipating the Future Frames of Video Sequences using Spatio-Temporal 3d Convolutions in Progressively Growing GANs"
date: 2018-11-26 16:14:45
categories: arXiv_CV
tags: arXiv_CV GAN Prediction
author: Sandra Aigner, Marco K&#xf6;rner
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a new encoder-decoder GAN model, FutureGAN, that predicts future frames of a video sequence conditioned on a sequence of past frames. During training, the networks solely receive the raw pixel values as an input, without relying on additional constraints or dataset specific conditions. To capture both the spatial and temporal components of a video sequence, spatio-temporal 3d convolutions are used in all encoder and decoder modules. Further, we utilize concepts of the existing progressively growing GAN (PGGAN) that achieves high-quality results on generating high-resolution single images. The FutureGAN model extends this concept to the complex task of video prediction. We conducted experiments on three different datasets, MovingMNIST, KTH Action, and Cityscapes. Our results show that the model learned representations to transform the information of an input sequence into a plausible future sequence effectively for all three datasets. The main advantage of the FutureGAN framework is that it is applicable to various different datasets without additional changes, whilst achieving stable results that are competitive to the state-of-the-art in video prediction. Our code is available at https://github.com/TUM-LMF/FutureGAN.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.01325](http://arxiv.org/abs/1810.01325)

##### PDF
[http://arxiv.org/pdf/1810.01325](http://arxiv.org/pdf/1810.01325)

