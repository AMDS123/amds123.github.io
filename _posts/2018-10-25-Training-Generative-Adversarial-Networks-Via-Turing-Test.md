---
layout: post
title: "Training Generative Adversarial Networks Via Turing Test"
date: 2018-10-25 16:08:02
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Jianlin Su
mathjax: true
---

* content
{:toc}

##### Abstract
In this article, we introduce a new mode for training Generative Adversarial Networks (GANs). Rather than minimizing the distance of evidence distribution $\tilde{p}(x)$ and the generative distribution $q(x)$, we minimize the distance of $\tilde{p}(x_r)q(x_f)$ and $\tilde{p}(x_f)q(x_r)$. This adversarial pattern can be interpreted as a Turing test in GANs. It allows us to use information of real samples during training generator and accelerates the whole training procedure. We even find that just proportionally increasing the size of discriminator and generator, it succeeds on 256x256 resolution without adjusting hyperparameters carefully.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.10948](https://arxiv.org/abs/1810.10948)

##### PDF
[https://arxiv.org/pdf/1810.10948](https://arxiv.org/pdf/1810.10948)

