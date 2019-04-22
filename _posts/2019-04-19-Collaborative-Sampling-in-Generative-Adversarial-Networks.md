---
layout: post
title: "Collaborative Sampling in Generative Adversarial Networks"
date: 2019-04-19 12:18:25
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Optimization Quantitative
author: Yuejiang Liu, Parth Kothari, Alexandre Alahi
mathjax: true
---

* content
{:toc}

##### Abstract
A standard practice in Generative Adversarial Networks (GANs) is to completely discard the discriminator when generating samples. However, this sampling method loses valuable information learned by the discriminator regarding the data distribution. In this work, we propose a collaborative sampling scheme between the generator and the discriminator for improved data generation. Guided by the discriminator, our approach refines generated samples through gradient-based optimization at a particular layer of the generator, shifting the generator distribution closer to the real data distribution. Additionally, we present a practical discriminator shaping method that can smoothen the loss landscape and further improve the sample refinement process. Through experiments on synthetic and image datasets, we demonstrate that our proposed method is able to improve generated samples both quantitatively and qualitatively, offering a new degree of freedom in GAN sampling. We finally show its potential for tackling mode collapse as well as adversarial examples.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1902.00813](https://arxiv.org/abs/1902.00813)

##### PDF
[https://arxiv.org/pdf/1902.00813](https://arxiv.org/pdf/1902.00813)

