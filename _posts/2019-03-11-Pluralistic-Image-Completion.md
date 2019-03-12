---
layout: post
title: "Pluralistic Image Completion"
date: 2019-03-11 11:44:56
categories: arXiv_CV
tags: arXiv_CV Attention GAN Face Relation
author: Chuanxia Zheng, Tat-Jen Cham, Jianfei Cai
mathjax: true
---

* content
{:toc}

##### Abstract
Most image completion methods produce only one result for each masked input, although there may be many reasonable possibilities. In this paper, we present an approach for pluralistic image completion - the task of generating multiple and diverse plausible solutions for image completion. A major challenge faced by learning-based approaches is that usually only one ground truth training instance per label. As such, sampling from conditional VAEs still leads to minimal diversity. To overcome this, we propose a novel and probabilistically principled framework with two parallel paths. One is a reconstructive path that extends the VAE through a latent space that covers all partial images with different mask sizes, and imposes priors that adapt to the number of pixels. The other is a generative path for which the conditional prior is coupled to distributions obtained in the reconstructive path. Both are supported by GANs. We also introduce a new short+long term attention layer that exploits distant relations among decoder and encoder features, improving appearance consistency. When tested on datasets with buildings (Paris), faces (CelebAHQ), and natural images (ImageNet), our method not only generated higher-quality completion results, but also with multiple and diverse plausible outputs.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.04227](https://arxiv.org/abs/1903.04227)

##### PDF
[https://arxiv.org/pdf/1903.04227](https://arxiv.org/pdf/1903.04227)

