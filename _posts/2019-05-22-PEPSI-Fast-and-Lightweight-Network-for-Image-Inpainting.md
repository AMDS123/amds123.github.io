---
layout: post
title: "PEPSI++: Fast and Lightweight Network for Image Inpainting"
date: 2019-05-22 08:18:48
categories: arXiv_CV
tags: arXiv_CV Adversarial Attention GAN Prediction
author: Yong-Goo Shin, Min-Cheol Sagong, Yoon-Jae Yeo, Seung-Wook Kim, Sung-Jea Ko
mathjax: true
---

* content
{:toc}

##### Abstract
Generative adversarial network (GAN)-based image inpainting methods which utilize coarse-to-fine network with a contextual attention module (CAM) have shown remarkable performance. However, they require numerous computational resources such as convolution operations and network parameters due to two stacked generative networks, which results in a low speed. To address this problem, we propose a novel network structure called PEPSI: parallel extended-decoder path for semantic inpainting network, which aims at not only reducing hardware costs but also improving the inpainting performance. The PEPSI consists of a single shared encoding network and parallel decoding networks with coarse and inpainting paths. The coarse path generates a preliminary inpainting result to train the encoding network for prediction of features for the CAM. At the same time, the inpainting path results in higher inpainting quality with refined features reconstructed using the CAM. In addition, we propose a Diet-PEPSI which significantly reduces the network parameters while maintaining the performance. In the proposed method, we present a Diet-PEPSI unit (DPU) which effectively aggregates the global contextual information with a small number of parameters. Extensive experiments and comparisons with state-of-the-art image inpainting methods demonstrate that both PEPSI and Diet-PEPSI achieve significant improvements in qualitative scores and reduced computation cost.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.09010](http://arxiv.org/abs/1905.09010)

##### PDF
[http://arxiv.org/pdf/1905.09010](http://arxiv.org/pdf/1905.09010)

