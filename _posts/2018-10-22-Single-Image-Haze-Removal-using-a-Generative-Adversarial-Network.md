---
layout: post
title: "Single Image Haze Removal using a Generative Adversarial Network"
date: 2018-10-22 18:04:50
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Inference
author: Bharath Raj N., Venkateswaran N
mathjax: true
---

* content
{:toc}

##### Abstract
Single image haze removal is an under constrained problem due to lack of depth information. It is usually performed by estimating the transmission map directly or by using a prior. Other methods use predictive models to estimate the transmission map and perform guided dehazing. In this paper, we propose a conditional GAN, that can directly remove haze from an image, without explicitly estimating transmission map or haze relevant features. We find that, only one module, comprising of the generator and discriminator is enough. We replaced the classic U-Net with the Tiramisu model, yielding much higher parameter efficiency and performance. We also observe that the performance during inference is dependent on the diversity of the dataset used for training. Experiments on synthetic and real world hazy images prove that our model performs competitively with the state of the art models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.09479](http://arxiv.org/abs/1810.09479)

##### PDF
[http://arxiv.org/pdf/1810.09479](http://arxiv.org/pdf/1810.09479)

