---
layout: post
title: "Diverse and Accurate Image Description Using a Variational Auto-Encoder with an Additive Gaussian Encoding Space"
date: 2017-11-19 20:12:43
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption RNN
author: Liwei Wang, Alexander G. Schwing, Svetlana Lazebnik
mathjax: true
---

* content
{:toc}

##### Abstract
This paper explores image caption generation using conditional variational auto-encoders (CVAEs). Standard CVAEs with a fixed Gaussian prior yield descriptions with too little variability. Instead, we propose two models that explicitly structure the latent space around $K$ components corresponding to different types of image content, and combine components to create priors for images that contain multiple types of content simultaneously (e.g., several kinds of objects). Our first model uses a Gaussian Mixture model (GMM) prior, while the second one defines a novel Additive Gaussian (AG) prior that linearly combines component means. We show that both models produce captions that are more diverse and more accurate than a strong LSTM baseline or a "vanilla" CVAE with a fixed Gaussian prior, with AG-CVAE showing particular promise.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1711.07068](https://arxiv.org/abs/1711.07068)

##### PDF
[https://arxiv.org/pdf/1711.07068](https://arxiv.org/pdf/1711.07068)

