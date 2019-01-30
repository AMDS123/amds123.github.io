---
layout: post
title: "PA-GAN: Improving GAN Training by Progressive Augmentation"
date: 2019-01-29 17:47:39
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Dan Zhang, Anna Khoreva
mathjax: true
---

* content
{:toc}

##### Abstract
Training of Generative Adversarial Networks (GANs) is notoriously fragile, which partially attributed to the discriminator performing well very quickly; its loss converges to zero, providing no reliable backpropagation signal to the generator. In this work we introduce a new technique - progressive augmentation of GANs (PA-GAN) - that helps to mitigate this issue and thus improve the GAN training. The key idea is to gradually increase the task difficulty of the discriminator by progressively augmenting its input or feature space, enabling continuous learning of the generator. We show that the proposed progressive augmentation preserves the original GAN objective, does not bias the optimality of the discriminator and encourages the healthy competition between the generator and discriminator, leading to a better-performing generator. We experimentally demonstrate the effectiveness of PA-GAN across different architectures and on multiple benchmarks for the image generation task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.10422](http://arxiv.org/abs/1901.10422)

##### PDF
[http://arxiv.org/pdf/1901.10422](http://arxiv.org/pdf/1901.10422)

