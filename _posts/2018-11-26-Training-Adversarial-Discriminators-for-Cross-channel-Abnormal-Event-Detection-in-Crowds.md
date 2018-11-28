---
layout: post
title: "Training Adversarial Discriminators for Cross-channel Abnormal Event Detection in Crowds"
date: 2018-11-26 23:54:56
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Quantitative Detection
author: Mahdyar Ravanbakhsh, Enver Sangineto, Moin Nabi, Nicu Sebe
mathjax: true
---

* content
{:toc}

##### Abstract
Abnormal crowd behaviour detection attracts a large interest due to its importance in video surveillance scenarios. However, the ambiguity and the lack of sufficient abnormal ground truth data makes end-to-end training of large deep networks hard in this domain. In this paper we propose to use Generative Adversarial Nets (GANs), which are trained to generate only the normal distribution of the data. During the adversarial GAN training, a discriminator (D) is used as a supervisor for the generator network (G) and vice versa. At testing time we use D to solve our discriminative task (abnormality detection), where D has been trained without the need of manually-annotated abnormal data. Moreover, in order to prevent G learn a trivial identity function, we use a cross-channel approach, forcing G to transform raw-pixel data in motion information and vice versa. The quantitative results on standard benchmarks show that our method outperforms previous state-of-the-art methods in both the frame-level and the pixel-level evaluation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1706.07680](http://arxiv.org/abs/1706.07680)

##### PDF
[http://arxiv.org/pdf/1706.07680](http://arxiv.org/pdf/1706.07680)

