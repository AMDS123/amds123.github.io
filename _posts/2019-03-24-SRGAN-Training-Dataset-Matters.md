---
layout: post
title: "SRGAN: Training Dataset Matters"
date: 2019-03-24 04:28:58
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN Inference
author: Nao Takano, Gita Alaghband
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GANs) in supervised settings can generate photo-realistic corresponding output from low-definition input (SRGAN). Using the architecture presented in the SRGAN original paper [2], we explore how selecting a dataset affects the outcome by using three different datasets to see that SRGAN fundamentally learns objects, with their shape, color, and texture, and redraws them in the output rather than merely attempting to sharpen edges. This is further underscored with our demonstration that once the network learns the images of the dataset, it can generate a photo-like image with even a slight hint of what it might look like for the original from a very blurry edged sketch. Given a set of inference images, the network trained with the same dataset results in a better outcome over the one trained with arbitrary set of images, and we report its significance numerically with Frechet Inception Distance score [22].

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.09922](http://arxiv.org/abs/1903.09922)

##### PDF
[http://arxiv.org/pdf/1903.09922](http://arxiv.org/pdf/1903.09922)

